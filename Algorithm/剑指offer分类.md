<!-- GFM-TOC -->
* [数据结构](#数据结构)
    * [数组](#数组)
        * 	[二维数组中的查找](#二维数组中的查找)
        * 	[数组中重复的数字](#数组中重复的数字)
		*	[构建乘积数组](#构建乘积数组)
	* [字符串](#字符串)
		*	[替换空格](#替换空格)
		*	[正则表达式匹配](#正则表达式匹配)
		*	[表示数值的字符串](#表示数值的字符串)
		*	[字符流中第一个不重复的字符](#字符流中第一个不重复的字符)
	* [链表](#链表)
		*	[从尾到头打印链表](#从尾到头打印链表)
		*	[链表中倒数第k个结点](#链表中倒数第k个结点)
		*	[反转链表](#反转链表)
		*	[合并两个排序的链表](#合并两个排序的链表)
		*	[复杂链表的复制](#复杂链表的复制)
		*	[二叉搜索树与双向链表](#二叉搜索树与双向链表)
		*	[两个链表的第一个公共结点](#两个链表的第一个公共结点)
		*	[链表中环的入口结点](#链表中环的入口结点)
		*	[删除链表中重复的结点](#删除链表中重复的结点)
	* [栈和队列](#栈和队列)
		*	[用两个栈实现队列](#用两个栈实现队列)
		*	[栈的压入、弹出序列](#栈的压入、弹出序列)
		*	[滑动窗口的最大值](#滑动窗口的最大值)
	* [树](#树)
		*	[重建二叉树](#重建二叉树)
		*	[树的子结构](#树的子结构)
		*	[从上往下打印二叉树](#从上往下打印二叉树)
		*	[二叉搜索树的后序遍历序列](#二叉搜索树的后序遍历序列)
		*	[二叉树中和为某一值的路径](#二叉树中和为某一值的路径)
<!-- GFM-TOC -->
        
# 数据结构
## 数组
### 二维数组中的查找
[二维数组中的查找](https://www.nowcoder.com/practice/abc3fe2ce8e146608e868a70efebf62e?tpId=13&tqId=11154&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
在一个二维数组中（每个一维数组的长度相同），每一行都按照从左到右递增的顺序排序，每一列都按照从上到下递增的顺序排序。请完成一个函数，输入这样的一个二维数组和一个整数，判断数组中是否含有该整数。
```
```java
public class Solution {
    public boolean Find(int target, int [][] array) {
        int row = array.length, col = array[0].length;
        int i = 0,  j = col - 1;
        while( i < row && j >=0){
            if(array[i][j] == target)
                return true;
            else if(array[i][j] > target)
                j--;
            else
                i++;
        }
        return false;
    }
}
```
### 数组中重复的数字
[数组中重复的数字](https://www.nowcoder.com/practice/623a5ac0ea5b4e5f95552655361ae0a8?tpId=13&tqId=11203&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
在一个长度为n的数组里的所有数字都在0到n-1的范围内。 数组中某些数字是重复的，但不知道有几个数字是重复的。也不知道每个数字重复几次。请找出数组中任意一个重复的数字。 例如，如果输入长度为7的数组{2,3,1,0,2,5,3}，那么对应的输出是第一个重复的数字2。
解法一：哈希集
解法二：性质
```
```java
public class Solution {
    public boolean duplicate(int numbers[],int length,int [] duplication) {
        if(length == 0) return false;
        for(int i = 0; i < length; ++i){
            
            while(i != numbers[i]){
                if(numbers[i] == numbers[numbers[i]]){
                    duplication[0] = numbers[i];
                    return true;
                }
                int temp = numbers[i];
                numbers[i] = numbers[numbers[i]];
                numbers[temp] = temp;
            }
        }
        return false;
    }   
}
```
### 构建乘积数组
[构建乘积数组](https://www.nowcoder.com/practice/94a4d381a68b47b7a8bed86f2975db46?tpId=13&tqId=11204&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
给定一个数组A[0,1,...,n-1],请构建一个数组B[0,1,...,n-1],其中B中的元素B[i]=A[0]*A[1]*...*A[i-1]*A[i+1]*...*A[n-1]。不能使用除法。
```
```java
import java.util.ArrayList;
public class Solution {
    public int[] multiply(int[] A) {
        if(A.length < 0) return null;
        int[] left = new int[A.length];
        int[] res = new int[A.length];
        left[0] = 1;       
        for(int i = 1; i < A.length; ++i){
            left[i] = left[i - 1] * A[i - 1];
        }
        int right = 1;
        for(int i = A.length - 1; i >= 0; --i){
            res[i] = left[i] * right;
            right = A[i] * right;
        }
        return res;
    }
}
```
## 字符串
### 替换空格
[替换空格](https://www.nowcoder.com/practice/4060ac7e3e404ad1a894ef3e17650423?tpId=13&tqId=11155&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
请实现一个函数，将一个字符串中的每个空格替换成“%20”。例如，当字符串为We Are Happy.则经过替换之后的字符串为We%20Are%20Happy。
```
```java
public class Solution {
    public String replaceSpace(StringBuffer str) {
        StringBuffer res = new StringBuffer();
        for(int i = 0; i < str.length(); ++i){
            if(str.charAt(i) == ' ') res.append("%20");
            else res.append(str.charAt(i));
        }
        return res.toString();
    }
}
```
### 正则表达式匹配
[正则表达式匹配](https://www.nowcoder.com/practice/45327ae22b7b413ea21df13ee7d6429c?tpId=13&tqId=11205&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
请实现一个函数用来匹配包括'.'和'*'的正则表达式。模式中的字符'.'表示任意一个字符，而'*'表示它前面的字符可以出现任意次（包含0次）。 在本题中，匹配是指字符串的所有字符匹配整个模式。例如，字符串"aaa"与模式"a.a"和"ab*ac*a"匹配，但是与"aa.a"和"ab*a"均不匹配
```
```java
public class Solution {
    public boolean isMatch(String s, String p) {
        if(s == null || p == null) {
            return false;
        }
        boolean[][] state = new boolean[s.length() + 1][p.length() + 1];
        state[0][0] = true;
        // no need to initialize state[i][0] as false
        // initialize state[0][j]
        for (int j = 1; j < state[0].length; j++) {
            if (p.charAt(j - 1) == '*') {
                if (state[0][j - 1] || (j > 1 && state[0][j - 2])) {
                    state[0][j] = true;
                }
            } 
        }
        for (int i = 1; i < state.length; i++) {
            for (int j = 1; j < state[0].length; j++) {
                if (s.charAt(i - 1) == p.charAt(j - 1) || p.charAt(j - 1) == '.') {
                    state[i][j] = state[i - 1][j - 1];
                }
                if (p.charAt(j - 1) == '*') {
                    if (s.charAt(i - 1) != p.charAt(j - 2) && p.charAt(j - 2) != '.') {
                        state[i][j] = state[i][j - 2];//in this case, a* only counts as empty
                    } else { //a* counts as multiple a ;a* counts as single a;a* counts as empty;
                        state[i][j] = state[i - 1][j] || state[i][j - 1] || state[i][j - 2];
                    }
                }
            }
        }
        return state[s.length()][p.length()];
    }
}
```
### 表示数值的字符串
[表示数值的字符串](https://www.nowcoder.com/practice/6f8c901d091949a5837e24bb82a731f2?tpId=13&tqId=11206&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
请实现一个函数用来判断字符串是否表示数值（包括整数和小数）。例如，字符串"+100","5e2","-123","3.1416"和"-1E-16"都表示数值。 但是"12e","1a3.14","1.2.3","+-5"和"12e+4.3"都不是。
```
```java
public class Solution {
    public boolean isNumeric(char[] str) {
        String string = String.valueOf(str);
        return string.matches("[\\+-]?[0-9]*(\\.[0-9]*)?([eE][\\+-]?[0-9]+)?");
    }
}
```
### 字符流中第一个不重复的字符
[字符流中第一个不重复的字符](https://www.nowcoder.com/practice/6f8c901d091949a5837e24bb82a731f2?tpId=13&tqId=11206&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
请实现一个函数用来找出字符流中第一个只出现一次的字符。例如，当从字符流中只读出前两个字符"go"时，第一个只出现一次的字符是"g"。当从该字符流中读出前六个字符“google"时，第一个只出现一次的字符是"l"。
如果当前字符流没有存在出现一次的字符，返回#字符。
```
```java
public class Solution
{    
    int[] hashtable=new int[256];
    StringBuffer s=new StringBuffer();
    //Insert one char from stringstream
    public void Insert(char ch)
    {
        s.append(ch);
        if(hashtable[ch]==0)
            hashtable[ch]=1;
        else hashtable[ch]+=1;
    }
  //return the first appearence once char in current stringstream
    public char FirstAppearingOnce()
    {
      char[] str=s.toString().toCharArray();
      for(char c:str)
      {
          if(hashtable[c]==1)
              return c;
      }
      return '#';
    }
}
```
## 链表
### 从尾到头打印链表
[从尾到头打印链表](https://www.nowcoder.com/practice/d0267f7f55b3412ba93bd35cfa8e8035?tpId=13&tqId=11156&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个链表，按链表值从尾到头的顺序返回一个ArrayList。
```
```java
import java.util.Stack;
//使用递归实现,本质上递归就是栈
import java.util.ArrayList;
public class Solution {
    ArrayList<Integer> list = new ArrayList<Integer>();
    public ArrayList<Integer> printListFromTailToHead(ListNode listNode) {
        if(listNode != null){
            printListFromTailToHead(listNode.next);
            list.add(listNode.val);
        }
        return list;
    }
}
//使用栈实现
/*
import java.util.ArrayList;
public class Solution {
    public ArrayList<Integer> printListFromTailToHead(ListNode listNode) {
        Stack<Integer> stack = new Stack<Integer>();
        while(listNode != null){
            stack.push(listNode.val);
            listNode = listNode.next;
        }
        ArrayList<Integer> res = new ArrayList<Integer>();
        while(!stack.empty()) res.add(stack.pop());
        return res;
    }
}
*/
```
### 链表中倒数第k个结点
[链表中倒数第k个结点](https://www.nowcoder.com/practice/529d3ae5a407492994ad2a246518148a?tpId=13&tqId=11167&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个链表，输出该链表中倒数第k个结点。
```
```java
/*
//和leetcode 19类似，leetcode中remove需要注意头部问题。
public class Solution {
    public ListNode FindKthToTail(ListNode head,int k) {
        if(head==null || k<=0) return null;
        ListNode slow=head;
        ListNode fast=head;
        while(k!=1){
            if(fast.next==null) return null;
            fast=fast.next;
            --k;
        }
        while(fast.next!=null){
            slow=slow.next;
            fast=fast.next;
        }
        return slow;
    }
}
```
### 反转链表
[反转链表](https://www.nowcoder.com/practice/75e878df47f24fdc9dc3e400ec6058ca?tpId=13&tqId=11168&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个链表，反转链表后，输出新链表的表头。
```
```java
/*
public class Solution {
    public ListNode ReverseList(ListNode head) {
        if(head==null) return null;
        ListNode a=head.next;
        head.next=null;
        while(a!=null){
            ListNode temp=a.next;
            a.next=head;
            head=a;
            a=temp;
        }
        return head;
    }
}
/*
public class Solution {
    public ListNode ReverseList(ListNode head) {
        if(head == null || head.next == null)
            return head;
        ListNode temp = head.next;
        ListNode newHead = ReverseList(head.next);
        temp.next = head;
        head.next = null;
        return newHead;
    }
}
*/
```
### 合并两个排序的链表
[合并两个排序的链表](https://www.nowcoder.com/practice/d8b6b4358f774294a89de2a6ac4d9337?tpId=13&tqId=11169&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入两个单调递增的链表，输出两个链表合成后的链表，当然我们需要合成后的链表满足单调不减规则。。
```
```java
//递归版本.牢记。
public class Solution {
    public ListNode Merge(ListNode list1,ListNode list2) {
        if(list1==null)
            return list2;
        if(list2==null)
            return list1;
        ListNode res=null;
        if(list1.val<=list2.val){
            res = list1;
            res.next=Merge(list1.next,list2);
        }
        if(list1.val>list2.val){
            res = list2;
            res.next=Merge(list1,list2.next);
        }
        return res;
    }
}

//循环版本
/*
public class Solution {
    public ListNode Merge(ListNode list1,ListNode list2) {
        ListNode Merge = new ListNode(0);
        ListNode head = Merge;
        while(true){
            if(list1==null) {
                Merge.next=list2;
                break;
            }
            if(list2==null) {
                Merge.next=list1;
                break;
            }
            if(list1.val<=list2.val){
                Merge.next=new ListNode(list1.val);
                list1=list1.next;
                Merge=Merge.next;
            }
            else{
                Merge.next=new ListNode(list2.val);
                list2=list2.next;
                Merge=Merge.next;
            }
        }
        return head.next;
    }
}
*/
```
### 复杂链表的复制
[复杂链表的复制](https://www.nowcoder.com/practice/f836b2c43afc4b35ad6adc41ec941dba?tpId=13&tqId=11178&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个复杂链表（每个节点中有节点值，以及两个指针，一个指向下一个节点，另一个特殊指针指向任意一个节点），返回结果为复制后复杂链表的head。（注意，输出结果中请不要返回参数中的节点引用，否则判题程序会直接返回空）
```
```java
import java.util.HashMap;
/*
public class RandomListNode {
    int label;
    RandomListNode next = null;
    RandomListNode random = null;

    RandomListNode(int label) {
        this.label = label;
    }
}
*/
//哈希表.1.复制next，存进map  2.复制random
public class Solution {
    public RandomListNode Clone(RandomListNode pHead)
    {
        if(pHead == null) return null;
        HashMap<RandomListNode, RandomListNode> map = new HashMap<RandomListNode,RandomListNode>();
        RandomListNode pCur = pHead;
        RandomListNode node = new RandomListNode(0);
        while(pCur != null){
            RandomListNode t = new RandomListNode(pCur.label);
            map.put(pCur, t);
            node.next = t;
            node = t;
            pCur = pCur.next;
        }
        pCur = pHead;
        while(pCur != null){
            map.get(pCur).random = map.get(pCur.random);
            pCur = pCur.next;
        }
        return map.get(pHead);
    }
}
/*
//总-分
public class Solution {
    public RandomListNode Clone(RandomListNode pHead)
    {
        if(pHead == null) return null;
        RandomListNode pCur = pHead;
        while(pCur != null){
            RandomListNode pTemp = new RandomListNode(pCur.label);
            pTemp.next = pCur.next;
            pCur.next = pTemp;
            pCur = pTemp.next;
        }
        pCur = pHead;
        while(pCur != null){
            if(pCur.random != null)
                pCur.next.random = pCur.random.next;
            pCur = pCur.next.next;
        }
        pCur = pHead;
        RandomListNode cloneHead = pCur.next;
        while(pCur != null){
            RandomListNode node = pCur.next;
            pCur.next = node.next;
            if(node.next != null)
                node.next = node.next.next;
            pCur = pCur.next;
        }
        return cloneHead;
    }
}
*/
```
### 二叉搜索树与双向链表
[二叉搜索树与双向链表](https://www.nowcoder.com/practice/947f6eb80d944a84850b0538bf0ec3a5?tpId=13&tqId=11179&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一棵二叉搜索树，将该二叉搜索树转换成一个排序的双向链表。要求不能创建任何新的结点，只能调整树中结点指针的指向。
```
```java
/**
public class TreeNode {
    int val = 0;
    TreeNode left = null;
    TreeNode right = null;

    public TreeNode(int val) {
        this.val = val;

    }

}
*/
//直接用中序遍历
public class Solution {
    TreeNode head = null;
    TreeNode realHead = null;
    public TreeNode Convert(TreeNode pRootOfTree) {
        ConvertSub(pRootOfTree);
        return realHead;
    }
     
    private void ConvertSub(TreeNode pRootOfTree) {
        if(pRootOfTree==null) return;
        ConvertSub(pRootOfTree.left);
        if (head == null) {
            head = pRootOfTree;
            realHead = pRootOfTree;
        } else {
            head.right = pRootOfTree;
            pRootOfTree.left = head;
            head = pRootOfTree;
        }
        ConvertSub(pRootOfTree.right);
    }
}
/*
public class Solution {
    public TreeNode Convert(TreeNode pRootOfTree) {
        if(pRootOfTree == null) 
            return null;
        if(pRootOfTree.left == null && pRootOfTree.right == null)
            return pRootOfTree;
        TreeNode left = Convert(pRootOfTree.left);
        TreeNode p = left;
        while(p != null && p.right != null){
            p = p.right;
        }
        if(left != null){
            p.right = pRootOfTree;
            pRootOfTree.left = p;
        }
        TreeNode right = Convert(pRootOfTree.right);
        if(right != null){
            right.left = pRootOfTree;
            pRootOfTree.right = right;
        }
        return left!=null?left:pRootOfTree;
        
    }
}
*/
```
### 两个链表的第一个公共结点
[两个链表的第一个公共结点](https://www.nowcoder.com/practice/6ab1d9a29e88450685099d45c9e31e46?tpId=13&tqId=11189&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入两个链表，找出它们的第一个公共结点
```
```java
/*
public class ListNode {
    int val;
    ListNode next = null;

    ListNode(int val) {
        this.val = val;
    }
}*/
//利用环的思路，两个指针走过的路程相等
public class Solution {
    public ListNode FindFirstCommonNode(ListNode pHead1, ListNode pHead2) {
        if (pHead1 == null || pHead2 == null) return null;
        ListNode a = pHead1, b = pHead2;
        while (a != b) {
            a = (a != null) ? a.next : pHead2;
            b = (b != null) ? b.next : pHead1;
        }
        return a;
    }
}
/*
public class Solution {
    public ListNode FindFirstCommonNode(ListNode pHead1, ListNode pHead2) {
        if(pHead1 == null || pHead1 == null)
            return null;
         int num1 = 0, num2 = 0;
         ListNode head1 = pHead1, head2 = pHead2;
         while(head1 != null){
             head1 = head1.next;
             ++num1;
         }
         while(head2 != null){
             head2 = head2.next;
             ++num2;
         }
        int k = Math.abs(num1 - num2);
        if(num1 >= num2){
            while(k != 0){
                pHead1 = pHead1.next;
                --k;
            }
        }
        else{
            while(k != 0){
                pHead2 = pHead2.next;
                --k;
            }
        }
        while(pHead1 != pHead2){
            pHead1 = pHead1.next;
            pHead2 = pHead2.next;
        }
        return pHead1;
    }
}
*/
```
### 链表中环的入口结点
[链表中环的入口结点](https://www.nowcoder.com/practice/253d2c59ec3e4bc68da16833f79a38e4?tpId=13&tqId=11208&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
给一个链表，若其中包含环，请找出该链表的环的入口结点，否则，输出null。
```
```java
public class Solution {
    public ListNode EntryNodeOfLoop(ListNode pHead)
    {
        if(pHead == null || pHead.next == null || pHead.next.next == null) return null;
        ListNode walk = pHead.next, run = pHead.next.next;
        while(run != null && run.next != null && walk != run ){
            walk = walk.next;
            run = run.next.next;
        }
        if(run == null || run.next == null || run.next.next == null) return null;
        walk = pHead;
        while(walk != run){
            walk = walk.next;
            run = run.next;
        }
        return walk;
    }
}
```
### 删除链表中重复的结点
[删除链表中重复的结点](https://www.nowcoder.com/practice/fc533c45b73a41b0b44ccba763f866ef?tpId=13&tqId=11209&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
在一个排序的链表中，存在重复的结点，请删除该链表中重复的结点，重复的结点不保留，返回链表头指针。 例如，链表1->2->3->3->4->4->5 处理后为 1->2->5
```
```java
public class Solution {
    public ListNode deleteDuplication(ListNode pHead)
    {
        if(pHead == null || pHead.next == null) return pHead;
        ListNode pre = new ListNode(0),dummy = pre;
        pre.next = pHead;
        while(pre.next != null){
            ListNode cur = pre.next;
            while(cur.next != null && cur.val == cur.next.val){
                cur = cur.next;
            }
            if(pre.next != cur) pre.next = cur.next;
            else pre = pre.next;
        }
        return dummy.next;
    }
}
```
##  栈和队列
### 用两个栈实现队列
[用两个栈实现队列](https://www.nowcoder.com/practice/54275ddae22f475981afa2244dd448c6?tpId=13&tqId=11158&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
用两个栈来实现一个队列，完成队列的Push和Pop操作。 队列中的元素为int类型。
```
```java
import java.util.Stack;
public class Solution {
    Stack<Integer> stack1 = new Stack<Integer>();
    Stack<Integer> stack2 = new Stack<Integer>();
     
    public void push(int node) {
        stack1.push(node);
    }
     
    public int pop() {
        if(stack1 == null && stack2 == null)
            throw new RuntimeException("Queue is empty!");
        else if(stack2.empty()){
            while(!stack1.empty())
                stack2.push(stack1.pop());
        }
        return stack2.pop();
    }
}
```
### 栈的压入、弹出序列
[栈的压入、弹出序列](https://www.nowcoder.com/practice/d77d11405cc7470d82554cb392585106?tpId=13&tqId=11174&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入两个整数序列，第一个序列表示栈的压入顺序，请判断第二个序列是否可能为该栈的弹出顺序。假设压入栈的所有数字均不相等。例如序列1,2,3,4,5是某栈的压入顺序，序列4,5,3,2,1是该压栈序列对应的一个弹出序列，但4,3,5,1,2就不可能是该压栈序列的弹出序列。（注意：这两个序列的长度是相等的）
```
```java
public class Solution {
    public boolean IsPopOrder(int [] pushA,int [] popA) {
        if(pushA == null || popA == null) return false;
        Stack<Integer> stack = new Stack<>();
        int popIdx = 0;
        for(int i = 0; i < pushA.length; ++i){
            stack.push(pushA[i]);
            while(!stack.empty() && stack.peek() == popA[popIdx]){
                stack.pop();
                popIdx++;
            }
        }
        return stack.empty();
    }
}
```
### 滑动窗口的最大值
[滑动窗口的最大值](https://www.nowcoder.com/practice/1624bc35a45c42c0bc17d17fa0cba788?tpId=13&tqId=11217&tPage=4&rp=4&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
给定一个数组和滑动窗口的大小，找出所有滑动窗口里数值的最大值。例如，如果输入数组{2,3,4,2,6,2,5,1}及滑动窗口的大小3，那么一共存在6个滑动窗口，他们的最大值分别为{4,4,6,6,6,5}； 针对数组{2,3,4,2,6,2,5,1}的滑动窗口有以下6个： {[2,3,4],2,6,2,5,1}， {2,[3,4,2],6,2,5,1}， {2,3,[4,2,6],2,5,1}， {2,3,4,[2,6,2],5,1}， {2,3,4,2,[6,2,5],1}， {2,3,4,2,6,[2,5,1]}。
```
```java
import java.util.*;
public class Solution {
    public ArrayList<Integer> maxInWindows(int [] num, int size)
    {
        ArrayList<Integer> list = new ArrayList<Integer>();
        ArrayDeque<Integer> que = new ArrayDeque<>();
        if(num.length == 0 || size == 0)
            return list;
        for(int i = 0; i < num.length; ++i){
            if(!que.isEmpty() && i - que.peekFirst() >= size)
                que.poll();
            while(!que.isEmpty() && num[que.peekLast()] < num[i])
                que.pollLast();
            que.offer(i);
            if(i >= size - 1) list.add(num[que.peek()]);
        }
        return list;
    }
}
```
## 树
### 重建二叉树
[重建二叉树](https://www.nowcoder.com/practice/8a19cbe657394eeaac2f6ea9b0f6fcf6?tpId=13&tqId=11157&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入某二叉树的前序遍历和中序遍历的结果，请重建出该二叉树。假设输入的前序遍历和中序遍历的结果中都不含重复的数字。例如输入前序遍历序列{1,2,4,7,3,5,6,8}和中序遍历序列{4,7,2,1,5,3,8,6}，则重建二叉树并返回。
```
```java
public class Solution {
    public TreeNode reConstructBinaryTree(int [] pre,int [] in) {
        TreeNode root = helper(pre, in, 0, pre.length - 1, 0, in.length - 1);
        return root;
    }
    
    private TreeNode helper(int[] pre, int[] in, int preStart, int preEnd, int inStart, int inEnd){
        if(preStart > preEnd || inStart > inEnd)
            return null;
        TreeNode root = new TreeNode(pre[preStart]);
        for(int i = inStart; i <= inEnd; ++i){
            if(pre[preStart] == in[i]){
                root.left = helper(pre, in, preStart + 1, preStart + i - inStart, inStart, i - 1);
                root.right = helper(pre, in, preStart + i - inStart + 1, preEnd, i + 1, inEnd);
                break;
            }
        }
        return root;
    }
}
```
### 树的子结构
[树的子结构](https://www.nowcoder.com/practice/6e196c44c7004d15b1610b9afca8bd88?tpId=13&tqId=11170&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入两棵二叉树A，B，判断B是不是A的子结构。（ps：我们约定空树不是任意一个树的子结构）
```
```java
public class Solution {
    public boolean HasSubtree(TreeNode root1,TreeNode root2) {
        if(root2 == null) return false;
        if(root1 == null) return false;
        if(helper(root1, root2))
            return true;
        else
            return helper(root1.left, root2) || helper(root1.right, root2);
    }
    
    private boolean helper(TreeNode root1, TreeNode root2){
        if(root2 == null) return true;
        if(root1 == null) return false;
        if(root1.val != root2.val) return false;
        return helper(root1.left, root2.left) && helper(root1.right, root2.right);
    }
}
```
### 从上往下打印二叉树
[从上往下打印二叉树](https://www.nowcoder.com/practice/7fe2212963db4790b57431d9ed259701?tpId=13&tqId=11175&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
从上往下打印出二叉树的每个节点，同层节点从左至右打印。
```
```java
public class Solution {
    public ArrayList<Integer> PrintFromTopToBottom(TreeNode root) {
        ArrayList<Integer> list = new ArrayList<Integer>();
        if(root == null) return list;
        Queue<TreeNode> que = new LinkedList<TreeNode>();
        que.offer(root);
        while(!que.isEmpty()){
            TreeNode node = que.poll();
            if(node.left != null) que.offer(node.left);
            if(node.right != null) que.offer(node.right);
            list.add(node.val);
        }
        return list;
    }
}
```
### 二叉搜索树的后序遍历序列
[二叉搜索树的后序遍历序列](https://www.nowcoder.com/practice/a861533d45854474ac791d90e447bafd?tpId=13&tqId=11176&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个整数数组，判断该数组是不是某二叉搜索树的后序遍历的结果。如果是则输出Yes,否则输出No。假设输入的数组的任意两个数字都互不相同。
```
```java
public class Solution {
    public boolean VerifySquenceOfBST(int [] sequence) {
        if(sequence.length == 0) 
            return false;
        return helper(sequence, 0, sequence.length - 1);
    }
    
    private boolean helper(int[] sequence, int start, int end){
        if(start >= end) 
            return true;
        int root = sequence[end];
        int index = end - 1;
        while(index >= start && sequence[index] > root) 
            index--;
        int tmp = index;
        while(tmp >= start){
            if(sequence[tmp] < root) 
                tmp--;
            else
                return false;
        }
        return helper(sequence, start, index) && helper(sequence, index + 1, end - 1);
    }
}
```
### 二叉树中和为某一值的路径
[二叉树中和为某一值的路径](https://www.nowcoder.com/practice/b736e784e3e34731af99065031301bca?tpId=13&tqId=11177&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一颗二叉树的跟节点和一个整数，打印出二叉树中结点值的和为输入整数的所有路径。路径定义为从树的根结点开始往下一直到叶结点所经过的结点形成一条路径。(注意: 在返回值的list中，数组长度大的数组靠前)
```
```java
public class Solution {
    ArrayList<ArrayList<Integer>> res = new ArrayList<>();
    ArrayList<Integer> cur = new ArrayList<Integer>();
    public ArrayList<ArrayList<Integer>> FindPath(TreeNode root,int target) {      
        if(root == null) return res;
        cur.add(root.val);
        if(root.left == null && root.right == null && root.val == target)
            res.add(new ArrayList(cur));
        FindPath(root.left, target - root.val);
        FindPath(root.right, target - root.val);
        cur.remove(cur.size()-1); //不满足条件下要减去刚刚添加的节点值 
        return res;
    }
}
```











