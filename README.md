import java.awt.*;
import java.awt.event.*;
import javax.swing.*;

public static void main(String[] args) {
JFrame w=new JFrame("SwimTurtleSwim");
       w.setSize(1720,768);
       w.setBackground(Color.LIGHT_GRAY);
       w.add(mp);
       w.addMouseListener(mp);
       w.addMouseMotionListener(mp);
       
       w.addKeyListener(mp);
       mp.addKeyListener(mp);
       Thread ti=new Thread(mp);
       ti.start();
       w.show();
    }
}

class Mypan extends JPanel implements Runnable, MouseListener, MouseMotionListener, KeyListener{
  int x = 300;
  int y = 100;
   int[] m = new int[50];
   int[] n = new int[50];
   int[] q = new int[50];
   int[] a = new int[300];
   int[] b = new int[300];
   int[] c = new int[10];
   int[] d = new int[10];
int f = 0;
  Mypan(){
       for(int i=0; i<300; i++){
       
       }
       for(int j=0; j<50; j++){
       
       }
       for(int k=0; k<10; k++){
       
       }
  }
  public void paintComponent(Graphics g){
      super.paintComponent(g);
      this.setBackground(Color.cyan);
      for(int j=0; j<50; j++){
      
      }
      for(int k=0; k<10; k++){
       
      }
      if(fan==true){
      if(mov==true){
      
          }
else{
  }
 }
else{
        }
        if(fan==true){
        if(mov==true){
            
            }
else{
        }
      }else{
      
      }
      if(fan==true){
          if(mov==true){
          }else{
          }
      }else{
      }
      if(fan==true){
          if(mov==true){
          }else{
}
      }else{
      }
     }
   public void run(){
        while(true){
          ga++;
          if(ga>20){
            ga = 0;
            f(mov==true){
              mov=false;
              }else {
              mov = true;
                  }
               }
               
               if(f==0){
               x++;
               y++;
               }
               if(f==1){
                  x--;
                  y++;
               }
               
               for(int i=0; i<300; i++){
                  a[i]--;
                  if(a[i]<0){
                      a[i]=1720;
                  }
               }
               for(int j=0; j<50; j++){
                   n[j]--;
                   if(n[j]<2){
                        n[j]=1720;
                   }
               }
               for(int k=0; k<10; k++){
                   c[k]=c[k]+2;
                   if(c[k]>1720){
                        c[k]=0;
                   }
               }
               try{
               Thread.sleep(20);
               }catch(Exception e){}
               repaint();
      }
}
