# 4.9
#define _CRT_SECURE_NO_WARNINGS 1
#include<iostream>

using namespace std;

int main()
{

}


//int main()
//{
//	int nums[]{8, 4, 2, 1, 23, 344, 12};
//	int numsLen = sizeof(nums) / sizeof(int);//计算出数组的长度
//	int sum = 0;
//	for (int i = 0; i < numsLen; i++)
//	{
//		cout << nums[i] << '\t';
//
//	}
//	cout << endl;
//	//累加操作
//	for (int i = 0; i < numsLen; i++)
//	{
//		sum += nums[i];
//	}
//	cout << "数列的和为：" << sum << "平均值为：" << sum / numsLen << endl;
//	//1.求数组中的最大值和最小值 - 打擂台  you can you up!no can no bibi!
//	
//	int max = nums[0];//假设第一个元素是最大值
//	int maxIndex = 0;//最大值的下标
//	int min = nums[0];//假设第一个元素是最小值
//	int minIndex=0;
//	for (int i = 1; i < numsLen; i++)
//	{
//		if (nums[i]>max)
//		{
//			max = nums[i];//留下买路钱
//			maxIndex = i;//记录下最大值的下标
//		}
//		if (nums[i] < min)
//		{
//			min = nums[i];
//			minIndex = i;//记录下最小值的下标
//		}
//	}
//	cout << "最大值是：" << max << '/' << nums[maxIndex] << endl;
//	cout << "最大值的下标是：" << maxIndex << endl;
//	cout << "最小值是：" << min << '/' << nums[minIndex] << endl;
//	cout << "最小值的下标是：" << minIndex << endl;
//
//	//2.定义一个整形数组，赋值后求出奇数个数和偶数个数
//	int jCount = 0, oCount = 0;
//	for (int i = 0; i < numsLen; i++)
//	{
//		if (nums[i] % 2 == 0)
//
//		{
//			oCount++;
//		}
//		else
//		{
//			jCount++;
//		}
//	}
//	cout << "奇数个数：" << jCount << '\t' << "偶数个数：" << oCount << endl;
//
//
//	//3.查找输入的数字在数组中的下标，没有找到则下标为-1
//	int searchNum;//用户要查找的数字
//	int searchIndex = INT_MIN;//用户查找数字的下标  --故意设定这个值是不可能的
//	cout << "请输入要查找的数字：";
//	cin >> searchNum;
//	//使用循环查找
//	for (int i = 0; i < numsLen; i++)
//	{
//		if (nums[i] == searchNum)
//		{
//			searchIndex = i;//记录下查找到元素的下标
//			break;
//		}
//	}
//	if (searchIndex == INT_MIN)
//	{
//		cout << "数组中没有这个数字！" << endl;
//	}
//	else
//	{
//		cout << searchNum << "在数组中的下标为：" << searchIndex << endl;
//	}
//}





//int main()
//{
//	int nums[]{8, 4, 2, 1, 23, 344, 12};
//	int numsLen = sizeof(nums) / sizeof(int);//计算出数组的长度
//	int sum = 0;
//	for (int i = 0; i < numsLen; i++)
//	{
//		cout << nums[i] << '\t';
//
//	}
//	cout << endl;
//	//累加操作
//	for (int i=0; i < numsLen; i++)
//	{
//		sum += nums[i];
//	}
//	cout << "数列的和为：" << sum << "平均值为：" << sum / numsLen << endl;
//
//}

//int main()
//{
//	//动态地从键盘录入信息并赋值
//		const int N = 5;
//		int nums[N];
//		cout << "数组的大小：" << sizeof(nums) / sizeof(int) << endl;
//		for (int i = 0; i < N; i++)
//		{
//			cout << "请输入第" << (i + 1) << "个数组元素：";
//			cin >> nums[i];
//		}
//		for (int i = 0; i < N; i++)
//		{
//			cout << nums[i] << endl;
//			 
//		}
//}

//int main()
//{
//	//动态地从键盘录入信息并赋值
//	const int N = 5;
//	int nums[N];
//	for (int i = 0; i < N; i++)
//	{
//		cout << "请输入第" << (i + 1) << "个数组元素：";
//		cin >> nums[i];
//	}
//	for (int i = 0; i < N; i++)
//	{
//		cout << nums[i] << endl;
//		 
//	}
//}
//int main()
//{
//	int num[] = { 198, 98, 'c', 230 };
//	cout << num[2] << endl;
//
//}
