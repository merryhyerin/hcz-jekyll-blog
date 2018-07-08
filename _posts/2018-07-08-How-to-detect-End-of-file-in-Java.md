---
layout: post
title: How to detect End of file in Java
categories: others
---

<h1>Algorithm training</h1>

<br>

<p>BAEKJOON > 문제 > 단계별로 풀어보기 > 입/출력 받아보기 > 11719</p>

<h3>Problem</h3>

<blockquote><p>
입력이 주어진다. 입력은 최대 100줄로 이루어져 있고, 알파벳 소문자, 대문자, 공백, 숫자로만 이루어져 있다. 
각 줄은 100글자를 넘지 않으며, 빈 줄이 주어질 수도 있고, 각 줄의 앞 뒤에 공백이 있을 수도 있다.</p></blockquote>

<h3>Code</h3>

{% highlight python %}

import java.util.Scanner;

public class P11719 {

	public static void main(String[] args) {
		
		Scanner sc = new Scanner(System.in);
		String str;
		
		while(sc.hasNextLine()) {
			str = sc.nextLine();
			System.out.println(str);
		}
				
		sc.close();
		
	}

}

{% endhighlight %}
