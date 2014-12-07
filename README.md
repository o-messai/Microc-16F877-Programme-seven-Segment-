Microc-16F877-Programme-seven-Segment-
======================================

void main() {   TRISC = 0;   PORTC = 0;   TRISB = 0;   PORTB = 0;  for(;;) { int i =0 ;  int j =1 ;    for (j==1,i==0;i&lt;99;i++,j++) {        PORTB=i;        delay_ms(500);        PORTC=i;        }   } } //~!
