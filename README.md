# Prakticheskoe_zadanie_10
  
![](image.png)
  
----------------------------------------------------------------------------------------------------------------------------
## Zadanie 1

```
#include <iostream>

using namespace std;

int main() 
{
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    for (int i = 1; i <= N; i++)  
    {
        cout << i << " ";  
    }
    return 0;
}
```

----------------------------------------------------------------------------------------------------------------------------
## Zadanie 2

```
#include <iostream>

using namespace std;

int main() 
{
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    for (int i = N; i >= 1; i--)  
    {
        cout << i << " ";  
    }
    return 0;
}
```

----------------------------------------------------------------------------------------------------------------------------
## Zadanie 3

```
#include <iostream>

using namespace std;

int main()
{
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    int sum = 0;
    for (int i = 1; i <= N; i++) 
    {
        sum += i;
    }

    cout << sum;
    return 0;
}
```

----------------------------------------------------------------------------------------------------------------------------
## Zadanie 4

```
#include <iostream>

using namespace std;

int main()
{
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    for (int i = 1; i <= N; i++) 
    {
        if (i % 2 == 0)
        {
            cout << i << " ";
        }
    }

    return 0;
}
```

----------------------------------------------------------------------------------------------------------------------------
## Zadanie 5

```
#include <iostream>

using namespace std;

int main()
{
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;

    int sum = 0;
    for (int i = 1; i <= N; i++) 
    {
        if (i % 2 == 0)
        {
            sum ++;
        }
    }
    cout << sum;
    return 0;
}
```

----------------------------------------------------------------------------------------------------------------------------
## Zadanie 6

```
#include <iostream>

using namespace std;

int main()
{
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    int f = 1;

    for (int i = 1; i <= N; i++) 
    {
            f *= i;  
    }
    cout << f;

    return 0;
}
```

----------------------------------------------------------------------------------------------------------------------------
## Zadanie 7

```
#include <iostream>

using namespace std;

int main()
{
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    int s = 1;
    for (int i = 1; i <= 10; i++)
    {  
        cout << N <<  " * " << i << " = " << N * i << endl;
    }

    return 0;
}
```

----------------------------------------------------------------------------------------------------------------------------
## Zadanie 8

```
#include <iostream>

using namespace std;

int main()
{
    setlocale(LC_ALL, "Russian");

    int N;
    cin >> N;
    int s = 1;
    for (int i = 1; i <= N; i++)
    {  
        for (int j = 0; j < N; j++)
        {
            cout << "*";
        }
        cout << '\n';
    }

    return 0;
}
```
