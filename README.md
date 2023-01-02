# DataStructureConcept

# stack 
what is stack?

     ------------------------------------------------stack----------------------------------------------------------------
     
      stack is simply first in last out.
      Insertion and deletion happens at the same end.
      stack is the data structure which follows LIFO 
      insertion and deletion happens at the same end i.e., from the top of the stack
      stack is implemented through Array or linkedlist
      method :
      push()---- add element at the top of the stack
      pop()----remove element from the stack , remove element which is recently added.
      peek()---- print the element which is recently added.
      isEmpty()--- check the stack is empty or not , return type is boolean.
      
      
      Algorithm:
      
      Implementation using Array:
      Imagine array as stack in which we add element using push operation and remove element using pop operation.
      
      
      how to add element in an stack i.e., push operation
      push(int x){
          //first of all check the stack(array) is full or not.
          if (top == n)                                          // top is reference which firstly pointed to -1 and n is the size of stack 
            sysout("stack is full)
          top=top+1;
          arr[top]=x;
      }
      
      how to remove element from i.e, pop operation 
      
      pop(){
         // first of all check stack is empty or not if stack is empty so we cannot delete element.
         if(top == -1)
             sysout("stack is empty");
          
         sysout("top element"+arr[top]);
         top=top-1;
      }
      
      peek operation - fetch the first element of the stack but doesn't remove the element from the stack. It doesn't take any parameter but return element type  
      peek(){
           if(top == -1)
              sysout("no element to print");
           sysout("peek element is"+arr[top]);
      }
      
      
      isEmpty(){
            if(top == -1)
              return true;
            return false;
      }
      
      
      <img src=""  alt="stack"/>
     ![stack](/stack.png)
     
     ![stack](https://github.com/MangeshAru/DataStructureConcept/blob/main/stack.png)
      
     #Queue
     - Queue is linear data structure i.e., that arrange the data items in orderly manner.
     - Follow the first in first out property.
     - New element is added at **rear end**
     - Existing element is deleted from other side i.e., ** front end **
     
     ** types of queue **
     1. Simple Queue
     2. Circular Queue
     3. Deque(double ended queue)
     4. Priority Queue 
