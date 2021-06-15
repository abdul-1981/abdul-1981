package INHERITANCE;
public class GoodFanDemo{
		public static void main(String[] args) {
		GoodFan fan=new GoodFan();
		SpeedOne one=new SpeedOne();
		SpeedTwo Two=new SpeedTwo();
		SpeedOff Off=new SpeedOff();
		fan.one=Off;
		fan.doButton();
		}
}class GoodFan{
		Switch one;
		public void doButton() {
		System.out.println(one);
		}
		}
		class Switch{

		}
		class  SpeedOne extends Switch{
		}
		class SpeedTwo extends Switch{
		}
		class SpeedOff extends Switch{
		}

