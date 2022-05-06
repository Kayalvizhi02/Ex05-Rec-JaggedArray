# Ex05-Rec-JaggedArray
## Aim:

To write a C# program to create a sample CPU usage on a network with 4 nodes using a jagged array.

## Algorithm:

### Step1:

### Step2:

### Step3:

### Step4:

### Step5:


## Program:
```c#
using System;
class CPUactivity
{
    public static void Main(String[] args)
    {
        int[][] array = new int[4][];
        array[0] = new int[3];
        array[1] = new int[5];
        array[2] = new int[6];
        array[3] = new int[4];
        for (int i = 0; i < 4; i++)
        {
            for (int j = 0; j < array[i].Length; j++)
            {
                array[i][j] = i * j + 70;
            }
        }
        for (int i = 0; i < array.Length; i++)
        {
            for (int j = 0; j < array[i].Length; j++)
            {
                Console.WriteLine("CPU usage at node" + i + " is " + array[i][j] + "%");
            }
            Console.WriteLine();
        }
    }
}
```
## Output:

![img](https://user-images.githubusercontent.com/75413726/167161888-6bf6599d-513f-4fcd-80cf-ff514d308129.jpg)

## Result:
