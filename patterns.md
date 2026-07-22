```java
int boxIndex = (r/3) * 3 + (c/3); //Sudoku


for (int i = 0; i < n; i++) {
    prefix[i + 1] = prefix[i] + nums[i]; //Prefix Sum
}
int rangeSum = prefix[right + 1] - prefix[left];

for(int i = n ; i>0; i--){
    suffix[i - 1] = suffix[i] + nums[i - 1]; // Suffix Sum
}

length#string // encoding string 

ListNode slow = head; //SlowFast
ListNode fast = head.next;
while(fast!=null && fast.next!=null){
    slow = slow.next; // Jump 1
    fast = fast.next.next; // Jump 2
}
```


