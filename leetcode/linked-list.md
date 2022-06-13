## reverse-linked-list

### ans
```
class Solution:
    def reverseList(self, head: Optional[ListNode]) -> Optional[ListNode]:
        current = head
        previous = None
        while(current):
            next = current.next
            current.next = previous
            previous = current
            current = next
      
        return previous
```
