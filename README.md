# superKeyword

class main {
        int x = 5;
        public void display() {
            System.out.println("Display main ");
        }
    }
    public class usingSuper extends main {
        int y = 6;
        public void display() {
            System.out.println("Child class displaying" + y);
            
        }
        public void method() {
        usingSuper obj1 = new usingSuper();
        obj1.display();
        super.display();
        }
     public static void main(String[] args) {
        usingSuper obj2 = new usingSuper();
        obj2.method();
     }   
}
