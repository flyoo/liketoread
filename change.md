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
<<<<<<< HEAD
}

 我们发现，定义结构体和定义类，非常相似，一个差别在于，一个是class，一个是struct。。。
=======
}
>>>>>>> refs/remotes/origin/master
