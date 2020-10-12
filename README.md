# j-
public void add_1(string s1, string s2)
        {
            string _sum = s1 + s2;
            Console.WriteLine("进行加法的连接结果为" + _sum);
        }
        public void reduce_1(string s1, string s2)
        {
            bool h = s1.Contains(s2);
            string s3;
            if (h)
            {
                int i = s1.IndexOf(s2);
                s3 = s1.Remove(i, s2.Length);
                if (!s3.Contains(s2))
                {
                    Console.WriteLine("进行减法运算的结果" + s3.ToString());
                }
            }
            else
            {
                Console.WriteLine("无法进行减法");
            }
        }
        public void Equals(string s1, string s2)
        {
            if (s1.CompareTo(s2) == 0)
            {
                Console.WriteLine("输入的两个字符串相等");
            }
            else
                Console.WriteLine("输入的两个字符串不相等");
        }
