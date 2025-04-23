
using System;

class Program
{
    static void Main()
    {
        // تمرین ۱: چاپ عناصر آرایه
        int[] numbers1 = { 10, 20, 30, 40, 50 };
        for (int i = 0; i < numbers1.Length; i++)
        {
            Console.WriteLine("Element at index " + i + " is: " + numbers1[i]);
        }

        Console.WriteLine();

        // تمرین ۲: مجموع عناصر آرایه
        int[] numbers2 = { 10, 20, 30, 40, 50 };
        int sum = 0;
        for (int i = 0; i < numbers2.Length; i++)
        {
            sum += numbers2[i];
        }
        Console.WriteLine("Sum of all elements: " + sum);

        Console.WriteLine();

        // تمرین ۳: میانگین عناصر آرایه
        double average = (double)sum / numbers2.Length;
        Console.WriteLine("Average: " + average);

        Console.WriteLine();

        // تمرین ۴: پیدا کردن بزرگ‌ترین عدد
        int[] numbers3 = { 10, 90, 20, 40, 75 };
        int max = numbers3[0];
        for (int i = 1; i < numbers3.Length; i++)
        {
            if (numbers3[i] > max)
            {
                max = numbers3[i];
            }
        }
        Console.WriteLine("Maximum value: " + max);

        Console.WriteLine();

        // تمرین ۵: پیدا کردن کوچک‌ترین عدد
        int[] numbers4 = { 10, 5, 3, 8, 22 };
        int min = numbers4[0];
        for (int i = 1; i < numbers4.Length; i++)
        {
            if (numbers4[i] < min)
            {
                min = numbers4[i];
            }
        }
        Console.WriteLine("Minimum value: " + min);

        Console.WriteLine();

        // تمرین ۶: شمارش تعداد اعداد زوج
        int[] numbers5 = { 1, 2, 3, 4, 5, 6 };
        int evenCount = 0;
        for (int i = 0; i < numbers5.Length; i++)
        {
            if (numbers5[i] % 2 == 0)
            {
                evenCount++;
            }
        }
        Console.WriteLine("Even numbers count: " + evenCount);

        Console.WriteLine();

        // تمرین ۷: شمارش تعداد اعداد فرد
        int oddCount = 0;
        for (int i = 0; i < numbers5.Length; i++)
        {
            if (numbers5[i] % 2 != 0)
            {
                oddCount++;
            }
        }
        Console.WriteLine("Odd numbers count: " + oddCount);

        Console.WriteLine();

        // تمرین ۸: معکوس کردن آرایه
        int[] original = { 1, 2, 3, 4, 5 };
        Array.Reverse(original);
        Console.WriteLine("Reversed array: " + string.Join(", ", original));

        Console.WriteLine();

        // تمرین ۹: چاپ فقط عناصر بزرگتر از 10
        int[] numbers6 = { 3, 11, 15, 7, 25 };
        for (int i = 0; i < numbers6.Length; i++)
        {
            if (numbers6[i] > 10)
            {
                Console.WriteLine("Greater than 10: " + numbers6[i]);
            }
        }

        Console.WriteLine();

        // تمرین ۱۰: جستجو برای یک عدد خاص
        int[] numbers7 = { 4, 8, 15, 16, 23, 42 };
        int search = 15;
        bool found = false;
        for (int i = 0; i < numbers7.Length; i++)
        {
            if (numbers7[i] == search)
            {
                found = true;
                break;
            }
        }
        Console.WriteLine("Number found? " + found);

        Console.WriteLine();

        // تمرین ۱۱: آرایه با ورودی کاربر
        int[] userInput = new int[5];
        for (int i = 0; i < userInput.Length; i++)
        {
            Console.Write("Enter number " + (i + 1) + ": ");
            userInput[i] = Convert.ToInt32(Console.ReadLine());
        }
        Console.WriteLine("You entered: " + string.Join(", ", userInput));

        Console.WriteLine();

        // تمرین ۱۲: جایگزینی اعداد منفی با صفر
        int[] nums = { -5, 2, -3, 7 };
        for (int i = 0; i < nums.Length; i++)
        {
            if (nums[i] < 0)
            {
                nums[i] = 0;
            }
        }
        Console.WriteLine("After replacing negatives: " + string.Join(", ", nums));

        Console.WriteLine();

        // تمرین ۱۳: ضرب همه عناصر آرایه
        int[] numbers8 = { 2, 3, 4 };
        int product = 1;
        for (int i = 0; i < numbers8.Length; i++)
        {
            product *= numbers8[i];
        }
        Console.WriteLine("Product of elements: " + product);

        Console.WriteLine();

        // تمرین ۱۴: یافتن اندیس یک عنصر
        int[] numbers9 = { 9, 18, 27 };
        int target = 18;
        for (int i = 0; i < numbers9.Length; i++)
        {
            if (numbers9[i] == target)
            {
                Console.WriteLine("Index of target: " + i);
                break;
            }
        }

        Console.WriteLine();

        // تمرین ۱۵: محاسبه تفاضل بیشترین و کمترین مقدار
        int[] numbers10 = { 12, 5, 9, 21, 3 };
        int maxVal = numbers10[0];
        int minVal = numbers10[0];
        for (int i = 1; i < numbers10.Length; i++)
        {
            if (numbers10[i] > maxVal) maxVal = numbers10[i];
            if (numbers10[i] < minVal) minVal = numbers10[i];
        }
        Console.WriteLine("Difference: " + (maxVal - minVal));

        Console.WriteLine();

        // تمرین ۱۶: یافتن عناصر یکتا (unique)
        int[] numbers11 = { 1, 2, 2, 3, 4, 4, 5 };
        Console.WriteLine("Unique elements:");
        for (int i = 0; i < numbers11.Length; i++)
        {
            bool isUnique = true;
            for (int j = 0; j < numbers11.Length; j++)
            {
                if (i != j && numbers11[i] == numbers11[j])
                {
                    isUnique = false;
                    break;
                }
            }
            if (isUnique)
                Console.WriteLine(numbers11[i]);
        }

        Console.WriteLine();

        // تمرین ۱۷: مرتب‌سازی آرایه (صعودی)
        int[] numbers12 = { 9, 3, 5, 1, 7 };
        Array.Sort(numbers12);
        Console.WriteLine("Sorted ascending: " + string.Join(", ", numbers12));

        Console.WriteLine();

        // تمرین ۱۸: محاسبه تعداد عناصر آرایه
        int[] numbers13 = { 1, 2, 3, 4, 5 };
        Console.WriteLine("Length of array: " + numbers13.Length);

        Console.WriteLine();

        // تمرین ۱۹: مقایسه دو آرایه
        int[] a = { 1, 2, 3 };
        int[] b = { 1, 2, 3 };
        bool areEqual = true;
        if (a.Length == b.Length)
        {
            for (int i = 0; i < a.Length; i++)
            {
                if (a[i] != b[i])
                {
                    areEqual = false;
                    break;
                }
            }
        }
        else
        {
            areEqual = false;
        }
        Console.WriteLine("Arrays equal? " + areEqual);

        Console.WriteLine();

        // تمرین ۲۰: جمع اعداد زوج در آرایه
        int[] numbers14 = { 1, 2, 3, 4, 5, 6 };
        int evenSum = 0;
        for (int i = 0; i < numbers14.Length; i++)
        {
            if (numbers14[i] % 2 == 0)
            {
                evenSum += numbers14[i];
            }
        }
        Console.WriteLine("Sum of even numbers: " + evenSum);

        Console.ReadKey();
    }
}
