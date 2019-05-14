<!-- GFM-TOC -->
* [数据结构](#数据结构)
    * [数组](#数组)
        * 	[二维数组中的查找](#二维数组中的查找)
        * 	[数组中重复的数字](#数组中重复的数字)
		*	[构建乘积数组](#构建乘积数组)
		*	[顺时针打印矩阵 ](#顺时针打印矩阵 )
	* [字符串](#字符串)
		*	[替换空格](#替换空格)
		*	[正则表达式匹配](#正则表达式匹配)
		*	[表示数值的字符串](#表示数值的字符串)
		*	[字符流中第一个不重复的字符](#字符流中第一个不重复的字符)
		*	[左旋转字符串](#左旋转字符串)
		*	[翻转单词顺序列](#翻转单词顺序列)
		*	[把字符串转换成整数](#把字符串转换成整数)
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
		*	[包含min函数的栈](#包含min函数的栈)
	* [树](#树)
		*	[重建二叉树](#重建二叉树)
		*	[树的子结构](#树的子结构)
		*	[从上往下打印二叉树](#从上往下打印二叉树)
		*	[二叉搜索树的后序遍历序列](#二叉搜索树的后序遍历序列)
		*	[二叉树中和为某一值的路径](#二叉树中和为某一值的路径)
		*	[二叉树的深度](#二叉树的深度 )
		*	[平衡二叉树](#平衡二叉树 )
		*	[二叉树的下一个结点](#二叉树的下一个结点)
		*	[对称的二叉树](#对称的二叉树 )
		*	[按之字形顺序打印二叉树](#按之字形顺序打印二叉树)
		*	[把二叉树打印成多行](#把二叉树打印成多行 )
		*	[序列化二叉树](#序列化二叉树)
		*	[数据流中的中位数](#数据流中的中位数)
		*	[二叉搜索树的第k个结点 ](#二叉搜索树的第k个结点 )
		*	[二叉树的镜像  ](#二叉树的镜像  )
* [算法](#算法)
	* [查找和排序](#查找和排序)
		* [旋转数组的最小数字 ](#旋转数组的最小数字 )
		* [数组中出现次数超过一半的数字](#数组中出现次数超过一半的数字)
		* [最小的K个数](#最小的K个数)
		* [数组中只出现一次的数字](#数组中只出现一次的数字)
		* [数据流中的中位数](#数据流中的中位数)
		* [调整数组顺序使奇数位于偶数前面](#调整数组顺序使奇数位于偶数前面)
		* [数字在排序数组中出现的次数 ](#数字在排序数组中出现的次数 )
	* [递归和循环](#递归和循环)
		* [斐波那契数列](#斐波那契数列)
		* [跳台阶](#跳台阶)
		* [变态跳台阶 ](#变态跳台阶 )
		* [矩形覆盖](#矩形覆盖)
	* [DFS](#DFS)
	* [回溯法](#回溯法)
		* [字符串的排列](#字符串的排列)
		* [矩阵中的路径](#矩阵中的路径)
		* [矩形覆盖](#矩形覆盖)
	* [动态规划](#动态规划)
		* [连续子数组的最大和](#连续子数组的最大和)
* [其他](#其他)
	* [数学](#数学)
		* [二进制中1的个数 ](#二进制中1的个数 )
		* [数值的整数次方 ](#数值的整数次方 )
		* [整数中1出现的次数（从1到n整数中1出现的次数）](#整数中1出现的次数（从1到n整数中1出现的次数）)
		* [把数组排成最小的数 ](#把数组排成最小的数 )
		* [丑数](#丑数 )
	* [时间空间效率](#时间空间效率)
		* [第一个只出现一次的字符位置  ](#第一个只出现一次的字符位置  )
		* [数组中的逆序对 ](#数组中的逆序对 )
	* [其他](#其他)
		* [和为S的连续正数序列  ](#和为S的连续正数序列  )
		* [和为S的两个数字  ](#和为S的两个数字  )
		* [扑克牌顺子  ](#扑克牌顺子  )
		* [孩子们的游戏(圆圈中最后剩下的数)  ](#孩子们的游戏(圆圈中最后剩下的数)  )
		* [求1+2+3+...+n  ](#求1+2+3+...+n  )
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
### 顺时针打印矩阵
[顺时针打印矩阵](https://www.nowcoder.com/practice/9b4c81a02cd34f76be2659fa0d54342a?tpId=13&tqId=11172&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个矩阵，按照从外向里以顺时针的顺序依次打印出每一个数字，例如，如果输入如下4 X 4矩阵： 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 则依次打印出数字1,2,3,4,8,12,16,15,14,13,9,5,6,7,11,10.
```
```java
import java.util.ArrayList;
public class Solution {
    
    public ArrayList<Integer> printMatrix(int [][] matrix) {
        ArrayList<Integer> res = new ArrayList<Integer>();
        int m=matrix.length;
        int n=matrix[0].length;
        if(n == 0)
            return res;
        int layers=(Math.min(m,n) + 1)/2;
        for(int i=0;i<layers;++i){
            for(int j=i;j<n-i;++j)
                res.add(matrix[i][j]);
            for(int j=i+1;j<m-i;++j)
                res.add(matrix[j][n-i-1]);
            //判断是否会重复打印(从右向左的每行数据)奇数的时候
            for(int j=n-i-2;j>=i && (m-i-1!=i);--j)
                res.add(matrix[m-i-1][j]);
            for(int j=m-i-2;j>i && (n-i-1!=i);--j)
                res.add(matrix[j][i]);
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
### 左旋转字符串
[左旋转字符串](https://www.nowcoder.com/practice/12d959b108cb42b1ab72cef4d36af5ec?tpId=13&tqId=11196&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
汇编语言中有一种移位指令叫做循环左移（ROL），现在有个简单的任务，就是用字符串模拟这个指令的运算结果。对于一个给定的字符序列S，请你把其循环左移K位后的序列输出。例如，字符序列S=”abcXYZdef”,要求输出循环左移3位后的结果，即“XYZdefabc”。是不是很简单？OK，搞定它
```
```java
public class Solution {
    public String LeftRotateString(String str,int n) {
        if(str.length() == 0) return "";
        n = n % str.length();
        char[] strC = str.toCharArray();
        strC = Inverse(strC, 0, n - 1);
        strC = Inverse(strC, n, str.length() - 1);
        strC = Inverse(strC, 0, str.length() - 1);
        return new String(strC);
    }
    
    private char[] Inverse(char[] str, int i, int j){
        while(i < j){
            char temp = str[i];
            str[i] = str[j];
            str[j] = temp;
            i++;
            j--;
        }
        return str;
    }
}
```
### 翻转单词顺序列
[翻转单词顺序列](https://www.nowcoder.com/practice/3194a4f4cf814f63919d0790578d51f3?tpId=13&tqId=11197&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
牛客最近来了一个新员工Fish，每天早晨总是会拿着一本英文杂志，写些句子在本子上。同事Cat对Fish写的内容颇感兴趣，有一天他向Fish借来翻看，但却读不懂它的意思。例如，“student. a am I”。后来才意识到，这家伙原来把句子单词的顺序翻转了，正确的句子应该是“I am a student.”。Cat对一一的翻转这些单词顺序可不在行，你能帮助他么？
```
```java
public class Solution {
    public String ReverseSentence(String str) {
        char[] charSentence = str.toCharArray();
        int low = 0;
        int high = 0;
        while(low < charSentence.length ){
            if(high == charSentence.length || charSentence[high] == ' ' ){
                reverse(charSentence, low, high - 1);
                low = high + 1;
                ++high;
            }
            ++high;
        }
        return new String(reverse(charSentence, 0, str.length() - 1));
    }
    public char[] reverse(char[] charSentence, int low, int high){
        while(low < high){
            char temp = charSentence[low];
            charSentence[low] = charSentence[high];
            charSentence[high] = temp;
            ++low;
            --high;
        }
        return charSentence;
    }
}
```
### 把字符串转换成整数
[把字符串转换成整数](https://www.nowcoder.com/practice/1277c681251b4372bdef344468e4f26e?tpId=13&tqId=11202&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
将一个字符串转换成一个整数(实现Integer.valueOf(string)的功能，但是string不符合数字要求时返回0)，要求不能使用字符串转换整数的库函数。 数值为0或者字符串不是一个合法的数值则返回0。
```
```java
public class Solution {
    public int StrToInt(String str) {
        if(str.length() <=0) return 0;
        int sum = 0;
        for(int i = 0; i < str.length(); ++i){
            char temp = str.charAt(i);
            if( i == 0 && (temp == '+' || temp == '-')) continue;
            if((temp - '0') < 0 || (temp - '0') > 9) return 0;
            sum = sum * 10 + temp - '0';
        }
        return str.charAt(0) == '-'?sum*(-1):sum;
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
### 包含min函数的栈
[包含min函数的栈](https://www.nowcoder.com/practice/4c776177d2c04c2494f2555c9fcc1e49?tpId=13&tqId=11173&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
定义栈的数据结构，请在该类型中实现一个能够得到栈中所含最小元素的min函数（时间复杂度应为O（1））。
```
```java
public class Solution {

    Stack<Integer> stack = new Stack<>();
    int min = Integer.MAX_VALUE;
    public void push(int node) {
        if(node < min){
            stack.push(min);
            min = node;
        }
        stack.push(node);
    }
    
    public void pop() {
        if(stack.pop() == min)
            min = stack.pop();
    }
    
    public int top() {
        return stack.peek();
    }
    
    public int min() {
        return min;
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
### 二叉树的深度 
[二叉树的深度 ](https://www.nowcoder.com/practice/435fb86331474282a3499955f0a41e8b?tpId=13&tqId=11191&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一棵二叉树，求该树的深度。从根结点到叶结点依次经过的结点（含根、叶结点）形成树的一条路径，最长路径的长度为树的深度。
```
```java
public class Solution {
    public int TreeDepth(TreeNode root) {
        return (root == null)?0:(Math.max(TreeDepth(root.left), TreeDepth(root.right)) + 1);
    }
}
```
### 平衡二叉树  
[平衡二叉树  ](https://www.nowcoder.com/practice/8b3b95850edb4115918ecebdf1b4d222?tpId=13&tqId=11192&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一棵二叉树，判断该二叉树是否是平衡二叉树。
```
```java
//后序遍历,包含剪枝过程
public class Solution {
    public boolean IsBalanced_Solution(TreeNode root) {
        return getDepth(root) != -1;
    }
     
    public int getDepth(TreeNode root) {
        if(root == null)
            return 0;
        int left = getDepth(root.left);
        if(left == -1)
            return -1;
        int right = getDepth(root.right);
        if(right == -1)
            return -1;
        return Math.abs(left - right)>1 ? -1:Math.max(left, right)+1;
    }
}
 
//递归，重复计算节点，效率不高
/*
public class Solution {
    public boolean IsBalanced_Solution(TreeNode root) {
        if(root == null)
            return true;
        int left = TreeDepth(root.left);
        int right = TreeDepth(root.right);
        int diff = Math.abs(left - right);
        if(diff > 1)
            return false;
        else
            return IsBalanced_Solution(root.left) && IsBalanced_Solution(root.right);
             
    }
     
    public int TreeDepth(TreeNode root) {
        return root == null?0:Math.max(TreeDepth(root.left), TreeDepth(root.right)) + 1;
    }
}
*/
```
### 二叉树的下一个结点  
[二叉树的下一个结点  ](https://www.nowcoder.com/practice/9023a0c988684a53960365b889ceaf5e?tpId=13&tqId=11210&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
给定一个二叉树和其中的一个结点，请找出中序遍历顺序的下一个结点并且返回。注意，树中的结点不仅包含左右子结点，同时包含指向父结点的指针。
```
```java
public class Solution {
    public TreeLinkNode GetNext(TreeLinkNode pNode)
    {
        if(pNode == null) return null;
        if(pNode.right != null){//父节点情况下
            pNode = pNode.right;
            while(pNode.left != null)
                pNode = pNode.left;
            return pNode;
        }
        while(pNode.next != null){
            if(pNode.next.left == pNode)//如果是左节点
                return pNode.next;
            pNode = pNode.next; //如果是右节点
        }
        return null;
    }
}
```
### 对称的二叉树   
[对称的二叉树   ](https://www.nowcoder.com/practice/ff05d44dfdb04e1d83bdbdab320efbcb?tpId=13&tqId=11211&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
请实现一个函数，用来判断一颗二叉树是不是对称的。注意，如果一个二叉树同此二叉树的镜像是同样的，定义其为对称的。
```
```java
public class Solution {
    boolean isSymmetrical(TreeNode pRoot)
    {
        if(pRoot == null) return true;
        return helper(pRoot.left, pRoot.right);
    }
    private boolean helper(TreeNode left, TreeNode right){
        if(left == null && right == null) 
            return true;
        if(left == null || right == null)
            return false;
        if(left.val == right.val)
            return helper(left.left, right.right) && helper(left.right, right.left);
        return false;
    }
}
```
### 按之字形顺序打印二叉树   
[按之字形顺序打印二叉树](https://www.nowcoder.com/practice/91b69814117f4e8097390d107d2efbe0?tpId=13&tqId=11212&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
请实现一个函数按照之字形打印二叉树，即第一行按照从左到右的顺序打印，第二层按照从右至左的顺序打印，第三行按照从左到右的顺序打印，其他行以此类推。
```
```java
public class Solution {
    public ArrayList<ArrayList<Integer>> Print(TreeNode pRoot) {
        ArrayList<ArrayList<Integer>> list = new ArrayList<>();
        if(pRoot == null)
            return list;
        boolean order = true;
        Queue<TreeNode> que = new LinkedList<>();
        que.add(pRoot);
        int size = 1;
        while(!que.isEmpty()){
            ArrayList<Integer> temp = new ArrayList();
            for(int i = 0; i < size; ++i){
                TreeNode node = que.poll();
                if(order)
                    temp.add(node.val);
                else
                    temp.add(0, node.val);  
                if(node.left != null)
                    que.add(node.left);
                if(node.right != null)
                    que.add(node.right);
            }
            list.add(temp);
            size = que.size();
            order = !order;
        }
        return list;
    }

}
```
### 把二叉树打印成多行    
[把二叉树打印成多行 ](https://www.nowcoder.com/practice/445c44d982d04483b04a54f298796288?tpId=13&tqId=11213&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
请实现一个函数按照之字形打印二叉树，即第一行按照从左到右的顺序打印，第二层按照从右至左的顺序打印，第三行按照从左到右的顺序打印，其他行以此类推。
```
```java
public class Solution {
    ArrayList<ArrayList<Integer> > Print(TreeNode pRoot) {
        ArrayList<ArrayList<Integer> > res = new ArrayList<>();
        if(pRoot == null) return res;
        Queue<TreeNode> que = new LinkedList<>();
        que.offer(pRoot);
        while(!que.isEmpty()){
            ArrayList<Integer> list = new ArrayList<Integer>();
            int size = que.size();
            for(int i = 0; i < size; ++i){
                TreeNode node = que.poll();
                list.add(node.val);
                if(node.left != null) que.offer(node.left);
                if(node.right != null) que.offer(node.right);
            }
            res.add(new ArrayList<Integer>(list));
        }
        return res;
    } 
}

//用递归做的
/*
public class Solution {
    ArrayList<ArrayList<Integer> > Print(TreeNode pRoot) {
        ArrayList<ArrayList<Integer>> list = new ArrayList<>();
        depth(pRoot, 1, list);
        return list;
    }
     
    private void depth(TreeNode root, int depth, ArrayList<ArrayList<Integer>> list) {
        if(root == null) return;
        if(depth > list.size())
            list.add(new ArrayList<Integer>());
        list.get(depth -1).add(root.val);
         
        depth(root.left, depth + 1, list);
        depth(root.right, depth + 1, list);
    }
}
*/
```
### 序列化二叉树     
[序列化二叉树  ](https://www.nowcoder.com/practice/cf7e25aa97c04cc1a68c8f040e71fb84?tpId=13&tqId=11214&tPage=4&rp=4&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
请实现两个函数，分别用来序列化和反序列化二叉树
```
```java
public class Solution {
    public int index = -1;
    String Serialize(TreeNode root) {
        StringBuffer sb = new StringBuffer();
        if(root == null){
            sb.append("#,");
            return sb.toString();
        }
        sb.append(root.val + ",");
        sb.append(Serialize(root.left));
        sb.append(Serialize(root.right));
        return sb.toString();                
    }

    TreeNode Deserialize(String str) {
        index++;
        //int len = str.length();
        //if(index >= len){
        //    return null;
        //}
        String[] strr = str.split(",");
        TreeNode node = null;
        if(!strr[index].equals("#")){
            node = new TreeNode(Integer.valueOf(strr[index]));
            node.left = Deserialize(str);
            node.right = Deserialize(str);
        }        
        return node;
  }
}
*/
```
### 数据流中的中位数     
[数据流中的中位数](https://www.nowcoder.com/practice/9be0172896bd43948f8a32fb954e1be1?tpId=13&tqId=11216&tPage=4&rp=4&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
如何得到一个数据流中的中位数？如果从数据流中读出奇数个数值，那么中位数就是所有数值排序之后位于中间的数值。如果从数据流中读出偶数个数值，那么中位数就是所有数值排序之后中间两个数的平均值。我们使用Insert()方法读取数据流，使用GetMedian()方法获取当前读取数据的中位数。
```
```java
public class Solution {
 
    private int count = 0;
    private PriorityQueue<Integer> minHeap = new PriorityQueue<>();
    private PriorityQueue<Integer> maxHeap = new PriorityQueue<Integer>(15, new Comparator<Integer>() {
        @Override
        public int compare(Integer o1, Integer o2) {
            return o2 - o1;
        }
    });
  
    public void Insert(Integer num) {
        if (count %2 == 0) {//当数据总数为偶数时，新加入的元素，应当进入小根堆
        //（注意不是直接进入小根堆，而是经大根堆筛选后取大根堆中最大元素进入小根堆）
        //1.新加入的元素先入到大根堆，由大根堆筛选出堆中最大的元素
            maxHeap.offer(num);
            int filteredMaxNum = maxHeap.poll();
        //2.筛选后的【大根堆中的最大元素】进入小根堆
            minHeap.offer(filteredMaxNum);
        } else {//当数据总数为奇数时，新加入的元素，应当进入大根堆
            //（注意不是直接进入大根堆，而是经小根堆筛选后取小根堆中最大元素进入大根堆）
            //1.新加入的元素先入到小根堆，由小根堆筛选出堆中最小的元素
            minHeap.offer(num);
            int filteredMinNum = minHeap.poll();
            //2.筛选后的【小根堆中的最小元素】进入大根堆
            maxHeap.offer(filteredMinNum);
        }
        count++;
    }
  
    public Double GetMedian() {
        if (count %2 == 0) {
            return new Double((minHeap.peek() + maxHeap.peek())) / 2;
        } else {
            return new Double(minHeap.peek());
        }
    }
}
```
### 二叉搜索树的第k个结点      
[二叉搜索树的第k个结点 ](https://www.nowcoder.com/practice/ef068f602dde4d28aab2b210e859150a?tpId=13&tqId=11215&tPage=4&rp=4&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
给定一棵二叉搜索树，请找出其中的第k小的结点。例如， （5，3，7，2，4，6，8）    中，按结点数值大小顺序第三小结点的值为4。
```
```java
public class Solution {
   int index = 0; //计数器
    TreeNode KthNode(TreeNode root, int k)
    {
        if(root != null){ //中序遍历寻找第k个
            TreeNode node = KthNode(root.left,k);
            if(node != null) //给出返回条件
                return node;
            index ++;
            if(index == k)
                return root;
            node = KthNode(root.right,k);
            if(node != null)
                return node;
        }
        return null;
    }
}

/*
public class Solution {
    int count = 0;
    TreeNode res = null;
    TreeNode KthNode(TreeNode pRoot, int k)
    {
        if(k == 0) return null;
        helper(pRoot, k);
        return res;
    }
    
    public void helper(TreeNode pRoot, int k){
        
        if(pRoot == null) return;
        if(pRoot.left != null) helper(pRoot.left, k);
        count++;
        if(count == k){
            res = pRoot;
            return;
        }
        if(pRoot.right != null) helper(pRoot.right, k);
        if(count < k) res = null;
    }

}
*/
```
### 二叉树的镜像       
[二叉树的镜像  ](https://www.nowcoder.com/practice/564f4c26aa584921bc75623e48ca3011?tpId=13&tqId=11171&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
操作给定的二叉树，将其变换为源二叉树的镜像。
```
```java
/*
public class Solution {
    public void Mirror(TreeNode root) {
        if(root == null) return;
        TreeNode temp=root.left;
        root.left=root.right;
        root.right=temp;
        Mirror(root.left);
        Mirror(root.right);     
    }
}
*/
//增加判断提高运行效率
public class Solution {
    public void Mirror(TreeNode root) {
        if(root == null)
            return;
        if(root.left == null && root.right == null)
            return;
         
        TreeNode pTemp = root.left;
        root.left = root.right;
        root.right = pTemp;
         
        if(root.left != null)
            Mirror(root.left);
        if(root.right != null)
            Mirror(root.right);
    }
}
```
# 算法

## 查找和排序

### 旋转数组的最小数字      
[旋转数组的最小数字 ](https://www.nowcoder.com/practice/9f3231a991af4f55b95579b44b7a01ba?tpId=13&tqId=11159&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
把一个数组最开始的若干个元素搬到数组的末尾，我们称之为数组的旋转。 输入一个非减排序的数组的一个旋转，输出旋转数组的最小元素。 例如数组{3,4,5,1,2}为{1,2,3,4,5}的一个旋转，该数组的最小值为1。 NOTE：给出的所有元素都大于0，若数组大小为0，请返回0。
```
```java
public class Solution {
    public int minNumberInRotateArray(int [] array) {
        int low=0;
        int high=array.length-1;
        while(low<high){
            int mid=low+(high-low)/2;
            if(array[mid]>array[high])
                low=mid+1;
            else if(array[mid]<array[high])
                high=mid;
            else
                high--;
        }
        return array[low];
    }
}
```
### 数组中出现次数超过一半的数字      
[数组中出现次数超过一半的数字 ](https://www.nowcoder.com/practice/e8a1b01a2df14cb2b228b30ee6a92163?tpId=13&tqId=11181&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
数组中有一个数字出现的次数超过数组长度的一半，请找出这个数字。例如输入一个长度为9的数组{1,2,3,2,2,2,5,4,2}。由于数字2在数组中出现了5次，超过数组长度的一半，因此输出2。如果不存在则输出0。
```
```java
public class Solution {
    public int MoreThanHalfNum_Solution(int [] array) {
        if(array.length == 0)
            return 0;
        int major=0,count=0;
        for(int i:array){
            if(count==0){
                major=i;
                ++count;
            }
            else if(major==i){
                ++count;
            }
            else
                --count;
        }
        int max=0;
        for(int i:array){
            if(i==major)
                ++max;
        }
        return max>array.length/2?major:0;
    }
}
 
//排序O（nlogn）+O（n）
/*
import java.util.Arrays;
public class Solution {
    public int MoreThanHalfNum_Solution(int [] array) {
        if(array.length == 0)
            return 0;
        Arrays.sort(array);
        int max = 0;
        int num = 0;
        int temp = array[0];
        int res = array[0];
        for(int i=0;i<array.length;++i){
            if(array[i] != temp){
                res = num>=max?array[i-1]:res;
                max=Math.max(num,max);
                temp=array[i];
                num=0; 
            }
            ++num;
        }
        res = num>=max?array[array.length-1]:res;
        max=Math.max(num,max);
        return max>array.length/2?res:0;
    }
}
*/
```
### 最小的K个数      
[最小的K个数 ](https://www.nowcoder.com/practice/6a296eb82cf844ca8539b57c23e6e9bf?tpId=13&tqId=11182&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入n个整数，找出其中最小的K个数。例如输入4,5,1,6,2,7,3,8这8个数字，则最小的4个数字是1,2,3,4,。
```
```java
//基于堆实现的优先队列，可参考《算法》第二章。时间复杂度O（nlogk）。不用修改数据本身，适合海量数据。
/*
public class Solution {
    public ArrayList<Integer> GetLeastNumbers_Solution(int [] input, int k) {
        ArrayList<Integer> list = new ArrayList<Integer>();
        if(input==null||input.length==0||input.length<k){
            return list;
        }
        for(int i = (k/2-1); i >= 0; i--){
            adjustHeap(input, i, k-1);
        }
        for(int i = k; i < input.length; ++i){
            if(input[i] < input[0]){
                int temp = input[i];
                input[i] = input[0];
                input[0] = temp;
                adjustHeap(input, 0, k-1);
            }
        }
        for(int i = 0; i < k; ++i){
            list.add(input[i]);
        }
        return list;
    }
    
    public void adjustHeap(int[] array, int i, int len){
        int maxIndex = i;
        if(i*2+1<=len && array[i]<array[2*i+1])
            maxIndex = 2*i+1;
        if(2*i+2<=len && array[i]<array[2*i+2])
            maxIndex = 2*i+2;
        if(maxIndex != i){
            swap(array, i, maxIndex);
            adjustHeap(array, maxIndex, len);    
        }
    }
    
    public void swap(int[] array, int i, int j){
        int temp = array[i];
        array[i] = array[j];
        array[j] = temp;
    }
        
}
*/
//快排思想，时间复杂度O(n)

public class Solution {
    public ArrayList<Integer> GetLeastNumbers_Solution(int [] input, int k) {
        ArrayList<Integer> list = new ArrayList<Integer>();
        if(k<=0 || k>input.length)
            return list;
        int lo = 0;
        int hi = input.length - 1;
        while(lo < hi){
            int j = partition(input, 0,input.length-1);
            if(j<k-1){
                lo = j + 1;
            }
            if(j>k-1){
                hi = j - 1;
            }
        }
        for(int i=0; i<k; ++i){
            list.add(input[i]);
        }   
        return list;
    }
    
    public int partition(int[] array, int start, int end){
        int pivot = (int)(start + Math.random()*(end - start + 1));
        int small = start - 1;
        swap(array, pivot, end);
        for(int i=start; i<=end; ++i){
            if(array[i] <= array[end]){
                small++;
                if(i > small)
                    swap(array, i, small);
            }
        }
        return small;
    }
    
    public void swap(int[] array, int i, int j){
        int temp = array[i];
        array[i] = array[j];
        array[j] = temp;
    }
}
```
### 数组中只出现一次的数字      
[数组中只出现一次的数字 ](https://www.nowcoder.com/practice/e02fdb54d7524710a7d664d082bb7811?tpId=13&tqId=11193&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入n个整数，找出其中最小的K个数。例如输入4,5,1,6,2,7,3,8这8个数字，则最小的4个数字是1,2,3,4,。
```
```java
//num1,num2分别为长度为1的数组。传出参数
//将num1[0],num2[0]设置为返回结果
import java.util.*;
public class Solution {
    public void FindNumsAppearOnce(int [] array,int num1[] , int num2[]) {
        int diff = 0;
        for (int num : array) {
            diff ^= num;
        }
        // Get its last set bit
        diff &= -diff;
        for (int num : array)
        {
            if ((num & diff) == 0) 
                num1[0] ^= num;
            else 
                num2[0] ^= num;
        }
    }
}
/*哈希表
public class Solution {
    public void FindNumsAppearOnce(int [] array,int num1[] , int num2[]) {
        Map<Integer,Integer> map = new HashMap<>();
        for(int i = 0; i < array.length; ++i){
            if(map.containsKey(array[i]))
                map.put(array[i],map.get(array[i]) + 1);
            else
                map.put(array[i],1);
        }
        int[] num  = new int[2];
        int j = 0;
        for(int i = 0; i < array.length; ++i){
            if(map.get(array[i]) == 1)
                num[j++] = array[i];
        }
        num1[0] = num[0];
        num2[0] = num[1];
    }
}
*/
```
### 调整数组顺序使奇数位于偶数前面      
[调整数组顺序使奇数位于偶数前面](https://www.nowcoder.com/practice/beb5aa231adc45b2a5dcc5b62c93f593?tpId=13&tqId=11166&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个整数数组，实现一个函数来调整该数组中数字的顺序，使得所有的奇数位于数组的前半部分，所有的偶数位于数组的后半部分，并保证奇数和奇数，偶数和偶数之间的相对位置不变。
```
```java
//插入排序思想
public class Solution {
    public void reOrderArray(int [] array) {
        for(int i = 0; i < array.length; ++i){
            if((array[i] & 1) == 1){
                for(int j = i - 1; j >= 0; --j){
                    if((array[j] & 1) == 0){
                        int temp = array[j + 1];
                        array[j + 1] = array[j];
                        array[j] = temp;                       
                    }
                }
            }
        }
    }
}
```
### 数字在排序数组中出现的次数       
[数字在排序数组中出现的次数 ](https://www.nowcoder.com/practice/70610bf967994b22bb1c26f9ae901fa2?tpId=13&tqId=11190&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
统计一个数字在排序数组中出现的次数。
```
```java

//因为data中都是整数，所以可以稍微变一下，不是搜索k的两个位置，而是搜索k-0.5和k+0.5
//这两个数应该插入的位置，然后相减即可。
public class Solution {
    public int GetNumberOfK(int [] data , int k) {
        return biSearch(data, k+0.5) - biSearch(data, k-0.5) ;
    }

    private int biSearch(int[] data, double num){
        int s = 0, e = data.length-1;     
        while(s <= e){
            int mid = (e - s)/2 + s;
            if(data[mid] < num)
                s = mid + 1;
            else if(data[mid] > num)
                e = mid - 1;
        }
        return s;
    }
};
/*二分查找
public class Solution {
    public int GetNumberOfK(int [] array , int k) {
        int index = BinarySearch(array, k, 0, array.length - 1);
        int i = 0, j = 0;
        if(index == -1)
            return 0;
        while(index - i >=0 && array[index - i] == k)
            i++;
        while(index + j < array.length && array[index + j] == k)
            j++;
        return i + j - 1;
    }
    
    public int BinarySearch(int [] array, int k, int low, int high){
        if(low > high)
            return -1;
        int mid = (high + low)/2;
        if(array[mid] < k)
            return BinarySearch(array, k, mid + 1, high);
        if(array[mid] > k)
            return BinarySearch(array, k, low, mid - 1);
        else
            return mid;
    }
}
*/
```
## 递归和循环
### 斐波那契数列      
[斐波那契数列](https://www.nowcoder.com/practice/c6c7742f5ba7442aada113136ddea0c3?tpId=13&tqId=11160&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
大家都知道斐波那契数列，现在要求输入一个整数n，请你输出斐波那契数列的第n项（从0开始，第0项为0）。
```
```java
//采用动态规划解法，跳台阶类似。
//往往循环比递归在时间和空间上效率更高。
public class Solution {
    public int Fibonacci(int n) {
        int[] dp=new int[n+1];
        if(n<=1) return n;
        dp[0]=0;
        dp[1]=1;
        for(int i=2;i<=n;++i){
            dp[i]=dp[i-1]+dp[i-2];
        }
        return dp[n];
    }
}


//递归方法超时，重复计算太多。
/*
public class Solution {
    public int Fibonacci(int n) {
        if(n==0) return 0;
        if(n==1) return 1;
        return Fibonacci(n-1)+Fibonacci(n-2);
    }
}
*/
```
### 跳台阶      
[跳台阶](https://www.nowcoder.com/practice/8c82a5b80378478f9484d87d1c5f12a4?tpId=13&tqId=11161&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
一只青蛙一次可以跳上1级台阶，也可以跳上2级。求该青蛙跳上一个n级的台阶总共有多少种跳法（先后次序不同算不同的结果）。
```
```java
public class Solution {
    public int JumpFloor(int target) {
        if(target<=1) return 1;
        int[] dp=new int[target+1];
        dp[0]=1;
        dp[1]=1;
        for(int i=2;i<=target;++i){
            dp[i]=dp[i-1]+dp[i-2];
        }
        return dp[target];
    }
}
```
### 变态跳台阶      
[变态跳台阶](https://www.nowcoder.com/practice/22243d016f6b47f2a6928b4313c85387?tpId=13&tqId=11162&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
一只青蛙一次可以跳上1级台阶，也可以跳上2级……它也可以跳上n级。求该青蛙跳上一个n级的台阶总共有多少种跳法。
```
```java
/*
//时间复杂度达到O(n^2),空间复杂度也达到O(n)
public class Solution {
    public int JumpFloorII(int target) {
        if(target<=1) return 1;
        int[] dp=new int[target+1];
        dp[0] = 1;
        dp[1] = 1;
        for(int i=2;i<=target;++i){
            for(int j=0;j<i;++j){
                dp[i]=dp[i]+dp[j];
            }
        }
        return dp[target];
    }
}
*/
/*归纳总结规律
public class Solution {
    public int JumpFloorII(int target) {
        if(target<=1) return 1;
        int[] dp=new int[target+1];
        dp[0] = 1;
        dp[1] = 1;
        for(int i=2;i<=target;++i){
            dp[i]=2*dp[i-1];
        }
        return dp[target];
    }
}
*/

public class Solution {
    public int JumpFloorII(int target) {
        if(target<=0)
            return 0;
        return 1<<(target-1);
    }
}
```
### 矩形覆盖       
[矩形覆盖 ](https://www.nowcoder.com/practice/72a5a919508a4251859fb2cfb987a0e6?tpId=13&tqId=11163&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
我们可以用2*1的小矩形横着或者竖着去覆盖更大的矩形。请问用n个2*1的小矩形无重叠地覆盖一个2*n的大矩形，总共有多少种方法？
```
```java
public class Solution {
    public int RectCover(int target) {
        if(target<=2) return target;
        int[] dp=new int[target+1];
        dp[0]=1;
        dp[1]=1;
        for(int i=2;i<=target;++i){
            dp[i]=dp[i-1]+dp[i-2];
        }
        return dp[target];
    }
}
```
## 回溯法
### 字符串的排列
[字符串的排列](https://www.nowcoder.com/practice/fe6b651b66ae47d7acce78ffdd9a96c7?tpId=13&tqId=11180&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个字符串,按字典序打印出该字符串中字符的所有排列。例如输入字符串abc,则打印出由字符a,b,c所能排列出来的所有字符串abc,acb,bac,bca,cab和cba。
```
```java
//第一步：求所有可能出现在第一个位置的字符，即把第一个字符与后面所有字符交换；
//第二步：固定第一个字符，求后面所有字符的排列。
import java.util.ArrayList;
public class Solution {
    ArrayList<String> list = new ArrayList<>();
    public ArrayList<String> Permutation(String str) {
        Permutation(str.toCharArray(),0);
        return list;
    }
    public void Permutation(char[] c,int begin){
        if(begin==c.length-1)
        {
            list.add(new String(c));
            return;
        }
        for(int i=begin;i<c.length;i++){
            if(c[begin]!=c[i]||begin==i) //判断是否有元素重复，重复就不交换位置
            {
                 char temp = c[i];
                 for(int j=i;j>begin;j--)  //要满足字典排序，所以挨个挪位置
                     c[j]=c[j-1];
                 c[begin]=temp;
                 Permutation(c,begin+1);   //求后面所有字符的排列
                 temp= c[begin];
                 for(int j=begin;j<i;j++)  //挪回去
                     c[j]=c[j+1];
                 c[i]=temp;
            }
        }
    }
}
```
### 矩阵中的路径
[矩阵中的路径](https://www.nowcoder.com/practice/c61c6999eecb4b8f88a98f66b273a3cc?tpId=13&tqId=11218&tPage=4&rp=4&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
请设计一个函数，用来判断在一个矩阵中是否存在一条包含某字符串所有字符的路径。路径可以从矩阵中的任意一个格子开始，每一步可以在矩阵中向左，向右，向上，向下移动一个格子。如果一条路径经过了矩阵中的某一个格子，则之后不能再次进入这个格子。 例如 a b c e s f c s a d e e 这样的3 X 4 矩阵中包含一条字符串"bcced"的路径，但是矩阵中不包含"abcb"路径，因为字符串的第一个字符b占据了矩阵中的第一行第二个格子之后，路径不能再次进入该格子。
```
```java
/**
用一个状态数组保存之前访问过的字符，然后再分别按上，下，左，右递归
*/
public class Solution {
    public boolean hasPath(char[] matrix, int rows, int cols, char[] str) {
        int flag[] = new int[matrix.length];
        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                if (helper(matrix, rows, cols, i, j, str, 0, flag))
                    return true;
            }
        }
        return false;
    }
 
    private boolean helper(char[] matrix, int rows, int cols, int i, int j, char[] str, int k, int[] flag) {
        int index = i * cols + j;
        if (i < 0 || i >= rows || j < 0 || j >= cols || matrix[index] != str[k] || flag[index] == 1)
            return false;
        if(k == str.length - 1) return true;
        flag[index] = 1;
        if (helper(matrix, rows, cols, i - 1, j, str, k + 1, flag)
                || helper(matrix, rows, cols, i + 1, j, str, k + 1, flag)
                || helper(matrix, rows, cols, i, j - 1, str, k + 1, flag)
                || helper(matrix, rows, cols, i, j + 1, str, k + 1, flag)) {
            return true;
        }
        flag[index] = 0;
        return false;
    }
}
```
### 机器人的运动范围 
[机器人的运动范围 ](https://www.nowcoder.com/practice/6e5207314b5241fb83f2329e89fdecc8?tpId=13&tqId=11219&tPage=4&rp=4&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
地上有一个m行和n列的方格。一个机器人从坐标0,0的格子开始移动，每一次只能向左，右，上，下四个方向移动一格，但是不能进入行坐标和列坐标的数位之和大于k的格子。 例如，当k为18时，机器人能够进入方格（35,37），因为3+5+3+7 = 18。但是，它不能进入方格（35,38），因为3+5+3+8 = 19。请问该机器人能够达到多少个格子？
```
```java
import java.util.*;

public class Solution {
 
    public int movingCount(int threshold, int rows, int cols) {
        int flag[][] = new int[rows][cols]; //记录是否已经走过
        return helper(0, 0, rows, cols, flag, threshold);
    }
 
    private int helper(int i, int j, int rows, int cols, int[][] flag, int threshold) {
        if (i < 0 || i >= rows || j < 0 || j >= cols || numSum(i) + numSum(j)  > threshold || flag[i][j] == 1) return 0;    
        flag[i][j] = 1;
        return helper(i - 1, j, rows, cols, flag, threshold)
            + helper(i + 1, j, rows, cols, flag, threshold)
            + helper(i, j - 1, rows, cols, flag, threshold)
            + helper(i, j + 1, rows, cols, flag, threshold)
            + 1;
    }
 
    private int numSum(int i) {
        int sum = 0;
        do{
            sum += i%10;
        }while((i = i/10) > 0);
        return sum;
    }
}
/*
public class Solution {
    int count = 0;
    public int movingCount(int threshold, int rows, int cols)
    {
        int flag[][] = new int[rows][cols]; //记录是否已经走过
        helper(threshold, rows, cols, 0, 0, flag);
        return count;
    }
    
    public void helper(int threshold, int rows, int cols, int i, int j, int[][] flag){
        String str = Integer.toString(i) + Integer.toString(j);
        int thres = 0;
        for(int k = 0; k < str.length(); ++k){
            thres += Character.getNumericValue(str.charAt(k));
        }
        if(i < 0 || i >= rows || j < 0 || j >= cols || flag[i][j] == 1 || thres > threshold)
            return;
        count++;
        flag[i][j] = 1;
        helper(threshold, rows, cols, i - 1, j, flag);
        helper(threshold, rows, cols, i + 1, j, flag);
        helper(threshold, rows, cols, i, j - 1, flag);
        helper(threshold, rows, cols, i, j + 1, flag);
    }
}
*/
```
## 动态规划
### 连续子数组的最大和
[连续子数组的最大和 ](https://www.nowcoder.com/practice/459bd355da1549fa8a49e350bf3df484?tpId=13&tqId=11183&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
HZ偶尔会拿些专业问题来忽悠那些非计算机专业的同学。今天测试组开完会后,他又发话了:在古老的一维模式识别中,常常需要计算连续子向量的最大和,当向量全为正数的时候,问题很好解决。但是,如果向量中包含负数,是否应该包含某个负数,并期望旁边的正数会弥补它呢？例如:{6,-3,-2,7,-15,1,2,2},连续子向量的最大和为8(从第0个开始,到第3个为止)。给一个数组，返回它的最大连续子序列的和，你会不会被他忽悠住？(子向量的长度至少是1)
```
```java
public class Solution {
    public int FindGreatestSumOfSubArray(int[] array) {
        if(array.length <= 0)
            return 0;
        int[] dp = new int[array.length];
        dp[0] = array[0];
        int max = dp[0];
        for(int i = 1; i < array.length; ++i){
            dp[i] = array[i] + (dp[i-1]<=0?0:dp[i-1]);
            max = Math.max(max,dp[i]);
        }
        return max;
    }
}
```
# 其他

## 数学

### 二进制中1的个数        
[二进制中1的个数  ](https://www.nowcoder.com/practice/8ee967e43c2c4ec193b040ea7fbb10b8?tpId=13&tqId=11164&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个整数，输出该数二进制表示中1的个数。其中负数用补码表示。
```
```java
//负数在最高位补1,>>是带符号右移，>>>是不带符号右移。
/*
public class Solution {
    public int NumberOf1(int n) {
        int res=0;
        while(n!=0){
            if((n&1)==1) res++;
            n=n>>>1;
        }
        return res;
    }
}
*/
 
//使用带符号右移的解法
/*
public class Solution {
    public int NumberOf1(int n) {
        int res=0;
        int flag=1;
        while(flag!=0){
            if((n & flag)!=0) res++;
            flag=flag<<1;
            
        }
        return res;
    }
}
*/
 
//最优解
public class Solution {
    public int NumberOf1(int n) {
        int res=0;
        while(n!=0){
            ++res;
            n=n&(n-1);
        }
        return res;
    }
}
```
### 数值的整数次方        
[数值的整数次方  ](https://www.nowcoder.com/practice/1a834e5e3e1a4b7ba251417554e07c00?tpId=13&tqId=11165&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
给定一个double类型的浮点数base和int类型的整数exponent。求base的exponent次方。
```
```java
//1.边界值判断好2.快速幂
public class Solution {
    public double Power(double base, int exponent) {
        double res=1;
        double cur=base;
        int exp;
        if(exponent>0)
            exp=exponent;
        else if(exponent<0){
            if(base==0)
                throw new RuntimeException("分母不能为0");
            exp=-exponent;
        }
        else
            return 1;
        while(exp!=0){
            if((exp&1)==1)
                res*=cur;
            cur*=cur;
            exp=exp>>1;
        }
        return exponent>=0 ? res:(1/res); 
  }
}
```
### 整数中1出现的次数（从1到n整数中1出现的次数）        
[整数中1出现的次数（从1到n整数中1出现的次数）](https://www.nowcoder.com/practice/bd7f978302044eee894445e244c7eee6?tpId=13&tqId=11184&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
求出1~13的整数中1出现的次数,并算出100~1300的整数中1出现的次数？为此他特别数了一下1~13中包含1的数字有1、10、11、12、13因此共出现6次,但是对于后面问题他就没辙了。ACMer希望你们帮帮他,并把问题更加普遍化,可以很快的求出任意非负整数区间中1出现的次数（从1 到 n 中1出现的次数）。
```
```java
public class Solution {     
    public int NumberOf1Between1AndN_Solution(int n) {    
        int count = 0;//1的个数    
        int i = 1;//当前位    
        int current = 0,after = 0,before = 0;    
        while((n/i)!= 0){               
            current = (n/i)%10; //高位数字     
            before = n/(i*10); //当前位数字     
            after = n-(n/i)*i; //低位数字     //如果为0,出现1的次数由高位决定,等于高位数字 * 当前位数         
            if (current == 0)      
                count += before*i;     //如果为1,出现1的次数由高位和低位决定,高位*当前位+低位+1          
            else if(current == 1)      
                count += before * i + after + 1;          //如果大于1,出现1的次数由高位决定,//（高位数字+1）* 当前位数          
            else{              
                count += (before + 1) * i;          
            }         //前移一位          
            i = i*10;    
        }    
        return count;   
    } 
}

```
### 把数组排成最小的数       
[把数组排成最小的数](https://www.nowcoder.com/practice/8fecd3f8ba334add803bf2a06af1b993?tpId=13&tqId=11185&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个正整数数组，把数组里所有数字拼接起来排成一个数，打印能拼接出的所有数字中最小的一个。例如输入数组{3，32，321}，则打印出这三个数字能排成的最小数字为321323。
```
```java
import java.util.*;
public class Solution {
public String PrintMinNumber(int [] numbers) {
        if(numbers == null || numbers.length == 0) return "";
        int len = numbers.length;
        String[] str = new String[len];
        StringBuilder sb = new StringBuilder();
        for(int i = 0; i < len; i++){
            str[i] = String.valueOf(numbers[i]);
        }
        Arrays.sort(str,new Comparator<String>(){
            @Override
            public int compare(String s1, String s2) {
                String c1 = s1 + s2;
                String c2 = s2 + s1;
                return c1.compareTo(c2);
            }
        });
        for(int i = 0; i < len; i++){
            sb.append(str[i]);
        }
        return sb.toString();
    }
}
/*
public class Solution {
    public String PrintMinNumber(int [] numbers) {
        String res = new String();
        for(int i = 0; i < numbers.length; ++i){
            for(int j = i+1; j < numbers.length; ++j){
                int a = Integer.valueOf(numbers[i] + "" + numbers[j]);
                int b = Integer.valueOf(numbers[j] + "" + numbers[i]);
                if(a > b){
                    int temp = numbers[i];
                    numbers[i] = numbers[j];
                    numbers[j] = temp;
                }
            }
        }
        for(int i = 0; i < numbers.length; ++i){
            res = res + String.valueOf(numbers[i]);
        }
        return res;
    }
}
*/
```
### 丑数        
[丑数 ](https://www.nowcoder.com/practice/6aa9e04fc3794f68acf8778237ba065b?tpId=13&tqId=11186&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
把只包含质因子2、3和5的数称作丑数（Ugly Number）。例如6、8都是丑数，但14不是，因为它包含质因子7。 习惯上我们把1当做是第一个丑数。求按从小到大的顺序的第N个丑数。
```
```java
public class Solution {
    public int GetUglyNumber_Solution(int index) {
        if(index == 0) return 0;
        int[] dp=new int[index];
        dp[0]=1;
        int a=0,b=0,c=0;
        for(int i=1;i<index;i++){
            dp[i]=Math.min(Math.min(dp[a]*2,dp[b]*3),dp[c]*5);
            if(dp[i]/dp[a]==2)
                a++;
            if(dp[i]/dp[b]==3)
                b++;
            if(dp[i]/dp[c]==5)
                c++;
        }
        return dp[index-1];
    }
}
```
## 时间空间效率

### 第一个只出现一次的字符位置 
[第一个只出现一次的字符位置 ](https://www.nowcoder.com/practice/1c82e8cf713b4bbeb2a5b31cf5b0417c?tpId=13&tqId=11187&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
在一个字符串(0<=字符串长度<=10000，全部由字母组成)中找到第一个只出现一次的字符,并返回它的位置, 如果没有则返回 -1（需要区分大小写）.
```
```java
import java.util.HashMap;
public class Solution {
    public int FirstNotRepeatingChar(String str) {
        HashMap<Character, Integer> map = new HashMap<Character, Integer>();
        for(int i = 0; i < str.length(); ++i){
            if(map.containsKey(str.charAt(i)))
               map.put(str.charAt(i),map.get(str.charAt(i))+1);
            else{
               map.put(str.charAt(i),1);
            }
        }
        for(int i = 0; i < str.length(); ++i){
            if(map.get(str.charAt(i)) == 1)
                return i;
        }
        return -1;
    }
}
```
### 数组中的逆序对 
[数组中的逆序对 ](https://www.nowcoder.com/practice/96bd6684e04a44eb80e6a68efc0ec6c5?tpId=13&tqId=11188&tPage=2&rp=2&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
在数组中的两个数字，如果前面一个数字大于后面的数字，则这两个数字组成一个逆序对。输入一个数组,求出这个数组中的逆序对的总数P。并将P对1000000007取模的结果输出。 即输出P%1000000007
```
```java
//归并排序
import java.util.Arrays;
public class Solution {
    int count = 0;
    public int InversePairs(int [] array) {
        int[] sort = mergeSort(array);
        return count;
    }
      
    public int[] mergeSort(int[] array){
        if(array.length <= 1)
            return array;;
        int mid = array.length/2;
        int[] left = Arrays.copyOfRange(array, 0, mid);
        int[] right = Arrays.copyOfRange(array, mid, array.length);
        return merge(mergeSort(left), mergeSort(right));
    }
      
    public int[] merge(int[] left, int[] right){
        int[] temp = new int[left.length + right.length];
        for(int index = 0, i = 0, j = 0; index < left.length + right.length; ++index){
            if(i >= left.length)
                temp[index] = right[j++];
            else if(j >= right.length)
                temp[index] = left[i++];
            else if(left[i] < right[j])
                temp[index] = left[i++];
            else{
                temp[index] = right[j++];
                count = (count + left.length - i)%1000000007;
            }
        }
        return temp;
    }
}
```

## 其他
### 和为S的连续正数序列 
[和为S的连续正数序列 ](https://www.nowcoder.com/practice/c451a3fd84b64cb19485dad758a55ebe?tpId=13&tqId=11194&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
小明很喜欢数学,有一天他在做数学作业时,要求计算出9~16的和,他马上就写出了正确答案是100。但是他并不满足于此,他在想究竟有多少种连续的正数序列的和为100(至少包括两个数)。没多久,他就得到另一组连续正数和为100的序列:18,19,20,21,22。现在把问题交给你,你能不能也很快的找出所有和为S的连续正数序列? Good Luck!
```
```java
import java.util.ArrayList;
//双指针操作
public class Solution {
    public ArrayList<ArrayList<Integer> > FindContinuousSequence(int sum) {
        //存放结果
        ArrayList<ArrayList<Integer> > result = new ArrayList<>();
        //两个起点，相当于动态窗口的两边，根据其窗口内的值的和来确定窗口的位置和大小
        int plow = 1,phigh = 2;
        while(phigh > plow){
            //由于是连续的，差为1的一个序列，那么求和公式是(a0+an)*n/2
            int cur = (phigh + plow) * (phigh - plow + 1) / 2;
            //相等，那么就将窗口范围的所有数添加进结果集
            if(cur == sum){
                ArrayList<Integer> list = new ArrayList<>();
                for(int i=plow;i<=phigh;i++){
                    list.add(i);
                }
                result.add(list);
                plow++;
            //如果当前窗口内的值之和小于sum，那么右边窗口右移一下
            }else if(cur < sum){
                phigh++;
            }else{
            //如果当前窗口内的值之和大于sum，那么左边窗口右移一下
                plow++;
            }
        }
        return result;
    }
}

//找规律
/*
public class Solution {
    public ArrayList<ArrayList<Integer> > FindContinuousSequence(int sum) {
       ArrayList<ArrayList<Integer>> res = new ArrayList<>();
       for(int n = (int) Math.sqrt(2*sum); n >= 2; --n){
           if((n & 1) == 1 && sum%n == 0 || (sum%n)*2 == n){
               ArrayList<Integer> list = new ArrayList<>();
               for(int j = 0, k = sum/n - (n - 1)/2; j < n; ++j, ++k){
                   list.add(k);
               }
               res.add(list);
           }
       }
        return res;
    }
}
*/
```

### 和为S的两个数字 
[和为S的两个数字 ](https://www.nowcoder.com/practice/390da4f7a00f44bea7c2f3d19491311b?tpId=13&tqId=11195&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
输入一个递增排序的数组和一个数字S，在数组中查找两个数，使得他们的和正好是S，如果有多对数字的和等于S，输出两个数的乘积最小的。
```
```java
import java.util.ArrayList;
public class Solution {
    public ArrayList<Integer> FindNumbersWithSum(int [] array,int sum) {
        ArrayList<Integer> res = new ArrayList<Integer>();
        int l = 0, r = array.length - 1;
        while(l < r){
            if(array[l] + array[r] == sum){
                res.add(array[l]);
                res.add(array[r]);
                break;
            }
            else if(array[l] + array[r] < sum)
                l++;
            else
                r--;
        }
        return res;
    }
}
```
### 扑克牌顺子 
[扑克牌顺子 ](https://www.nowcoder.com/practice/762836f4d43d43ca9deb273b3de8e1f4?tpId=13&tqId=11198&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
LL今天心情特别好,因为他去买了一副扑克牌,发现里面居然有2个大王,2个小王(一副牌原本是54张^_^)...他随机从中抽出了5张牌,想测测自己的手气,看看能不能抽到顺子,如果抽到的话,他决定去买体育彩票,嘿嘿！！“红心A,黑桃3,小王,大王,方片5”,“Oh My God!”不是顺子.....LL不高兴了,他想了想,决定大\小 王可以看成任何数字,并且A看作1,J为11,Q为12,K为13。上面的5张牌就可以变成“1,2,3,4,5”(大小王分别看作2和4),“So Lucky!”。LL决定去买体育彩票啦。 现在,要求你使用这幅牌模拟上面的过程,然后告诉我们LL的运气如何， 如果牌能组成顺子就输出true，否则就输出false。为了方便起见,你可以认为大小王是0。
```
```java
//bit map 判断有重复数字思想
public class Solution {
    public boolean isContinuous(int [] numbers) {
        if(numbers.length != 5) return false;
        int max = -1;
        int min = 14;
        int flag = 0;
        for(int i = 0; i < numbers.length; ++i){
            int number  = numbers[i];
            if(number < 0 || number > 13) return false;
            if(number == 0) continue;
            if(((flag >> number) & 1) == 1) return false;
            flag |= (1 << number);
            if(number < min) min = number;
            if(number > max) max = number;
            if(max - min >4) return false;
        }
        return true;
    }
} 
/* 
import java.util.Arrays;
public class Solution {
    public boolean isContinuous(int [] numbers) {
        if(numbers.length != 5) return false;
        Arrays.sort(numbers);
        for(int i = 1; i < numbers.length; ++i){
            if(numbers[i] != 0 && numbers[i-1] != 0 && numbers[i] == numbers[i-1])
                return false;
        }
        int min  = 0;
        for(int i = 0; i < numbers.length; ++i){
            if(numbers[i] != 0){
                min = numbers[i];
                break;
            }
        }
        int max = numbers[numbers.length - 1];
        if(max - min == 0 || max - min <= 4)
            return true;
        else
            return false;
    }
} 
*/
```
### 孩子们的游戏(圆圈中最后剩下的数) 
[孩子们的游戏(圆圈中最后剩下的数) ](https://www.nowcoder.com/practice/f78a359491e64a50bce2d89cff857eb6?tpId=13&tqId=11199&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
每年六一儿童节,牛客都会准备一些小礼物去看望孤儿院的小朋友,今年亦是如此。HF作为牛客的资深元老,自然也准备了一些小游戏。其中,有个游戏是这样的:首先,让小朋友们围成一个大圈。然后,他随机指定一个数m,让编号为0的小朋友开始报数。每次喊到m-1的那个小朋友要出列唱首歌,然后可以在礼品箱中任意的挑选礼物,并且不再回到圈中,从他的下一个小朋友开始,继续0...m-1报数....这样下去....直到剩下最后一个小朋友,可以不用表演,并且拿到牛客名贵的“名侦探柯南”典藏版(名额有限哦!!^_^)。请你试着想下,哪个小朋友会得到这份礼品呢？(注：小朋友的编号是从0到n-1)
```
```java
/* 
public class Solution {
    public int LastRemaining_Solution(int n, int m) {
        if(n == 0)
            return -1;
        if(n == 1)
            return 0;
        else
            return (LastRemaining_Solution(n - 1, m) + m)%n;
    }
}
*/
//dp: f[n] = (f[n-1] + m) mod n
public class Solution {
    public int LastRemaining_Solution(int n, int m) {
        if(n == 0)
            return -1;
        int last = 0;
        for(int i = 2; i <= n; ++i){
            last = (last + m)%i;
        }
        return last;
    }
}
```
### 求1+2+3+...+n 
[求1+2+3+...+n ](https://www.nowcoder.com/practice/7a0da8fc483247ff8800059e12d7caf1?tpId=13&tqId=11200&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
求1+2+3+...+n，要求不能使用乘除法、for、while、if、else、switch、case等关键字及条件判断语句（A?B:C）。
```
```java
//递归和&& ||的短路特性
public class Solution {
    public int Sum_Solution(int n) {
        int sum = n;
        boolean ans = (n > 0) && ((sum += Sum_Solution(n - 1)) > 0);
        return sum;
    }
}
```
### 不用加减乘除做加法 
[不用加减乘除做加法 ](https://www.nowcoder.com/practice/59ac416b4b944300b617d4f7f111b215?tpId=13&tqId=11201&tPage=3&rp=3&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking)
```html
题目描述
写一个函数，求两个整数之和，要求在函数体内不得使用+、-、*、/四则运算符号。
```
```java
public class Solution {
    public int Add(int num1,int num2) {
        while(num1 != 0){
            int temp = num2 ^ num1;
            num1 = (num1 & num2) << 1;
            num2 = temp;
        }
        return num2;
    }
}
```











