static void Main(string[] args)
{
int[] a = new int[7];
for (int i = 0; i < a.Length; i++)
{
Console.WriteLine ("Enter the number");
a[i] = Convert.ToInt32 (Console.ReadLine 
());
}
BubbleSort(a);
Console.WriteLine ("The array after sorting is :");
for (int i = 0; i < a.Length; i++)
{
Console.Write (a[i] + " ");
}
} //Sarah Alrashedi

public static void BubbleSort (int[] a)
{
int temp;
for (int i = a.Length - 1; i >=o; i--) 
{
for (int j = 1; j <=i; j++)
{
if (a[j - 1] > a[j])
{
temp = a[j];

a[j] = a[j - 1];

a[j - 1] = temp;
}
}
}
