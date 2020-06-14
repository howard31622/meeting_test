# meeting_test
一些面試題目


### 題目
#### 給定一串字串，輸出時要是一串英文，而在掃描每個字中，如果遇到?就隨機給一個英文單字，但不會有相連的英文單字，input最大100000
     input : a?bx?   
     output : asbxk
     
     input : ??rld   
     output : world
     
     input : ??????????  
     output :alskdjoiur

### A developer wants to create a collection of methods which s(he) wants certain classes to compulsorlt define. Initally, s(he) wants to add 2 methods -myMeth1() and myMeth2(String) to the collection. Which of following options would be ideal to carry out this Implemention?
A

    public class sampleCollection{
        void myMeth1();
        void myMeth2(String input);
    }
    
B

    public interface sampleCollection{
        void myMeth1();
        void myMeth2(String input);
    }

C

    public static class sampleCollection{
        void myMeth1();
        void myMeth2(String input);
    }

D

    public interface sampleCollection{
        protected void myMeth1(){
        //Define method implementation 
        }
        protected void myMeth2(String input){
        //Define method implementation 
        }
    }