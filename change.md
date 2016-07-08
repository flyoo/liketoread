#一段小程序
namespace Mytest
{
    public class Program
    {
        static void Main(string[] args)
        {
            Point point = new Point(10, 20);

            Console.WriteLine(string.Format("x={0}, y={1}", point.x, point.y));
        }
    }

    public struct Point
    {
        public int x;

        public int y;

//	        public point(int x, int y)
//	        {
//	            this.x = x;
//	            this.y = y;
//	        }
    }
}