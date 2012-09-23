kevinhilt_code
==============

code for robotc and visual basic
void easeIn()
{
 while(SensorValue[rightEncoder]<185);
{
 motor[port2]=-1;
 motor[port3]=-1;
}