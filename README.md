# 0000001
int a, m;
            a = 0;
            m = int.Parse(Console.ReadLine());
            if (m < 10)
            {
                a = m;
            }
            else if (m < 100)
            {
                a = m / 10;
            }
            else if (m < 1000)
            {
                a = m / 100;
            }
            else if (m < 10000)
            {
                a = m / 1000;
            }
            else if (m < 100000)
            {
                a = m / 10000;
            }
            Console.WriteLine(a);
