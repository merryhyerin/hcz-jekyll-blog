---
layout: post
title: Print A+B in Java
categories: others
---

<h1>Algorithm training</h1>

<br>

<p>BAEKJOON > 문제 > 단계별로 풀어보기 > 입/출력 받아보기 > 1000</p>

<h3>Problem</h3>

<blockquote><p>두 정수 A와 B를 입력받은 다음, A+B를 출력하는 프로그램을 작성하시오.</p></blockquote>

<h3>Code</h3>

{% highlight python %}

import java.util.Scanner;

public class P1000 {

	public static void main(String[] args) {
		
		Scanner sc = new Scanner(System.in);
		int a, b;
		
		a = sc.nextInt();
		b = sc.nextInt();
		
		System.out.println(a+b);
		
		sc.close();

	}

}

{% endhighlight %}
