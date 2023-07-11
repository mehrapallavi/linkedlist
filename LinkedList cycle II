public class Solution {
    public ListNode detectCycle(ListNode head) {
        ListNode hare = head;
        ListNode turtle= head;

    while(hare!=null && hare.next!=null){
        hare = hare.next.next;
        turtle= turtle.next;
        
        if(hare == turtle){
        turtle=head;

        while(hare!=turtle){
            turtle=turtle.next;
            hare=hare.next;
        }
        return turtle;
    }
}
return null;
    }
}
