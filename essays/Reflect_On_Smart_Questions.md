---
layout: essay
type: essay
title: Reflect on Smart Questions
date: 2016-09-08
labels:
  - Open Source
  - Stack Overflow
  - Learning
---

What is Stack Overflow?

Everyone has questions, including those who develop and deploy software solutions. The most experienced programmers may find while working on a project that they have a problem that they cannot solve due to a gap of knowledge in an esoteric topic. All is not lost, for where there is a gap in one developer or user's knowledge, there's another, somewhere, who knows the answer. Unfortunately, up until fairly recently in humanity's history, these people have been mostly separated by great gulfs of space and time; where finding, querying and replying to each other was more hassle to seek these people out than it was worth, making those with pressing conundrums to instead resort to scouring reference guides, hoping that these resources covered the specific questions they had in a way that they understand. Today, thankfully, we have the internet and, more important to this essay, Stack Exchange to help in the quest to find answers.

Stack Exchange started as one community called Stack Overflow. Stack Overflow is a site which allows programmers to answer questions within their fields of expertise and ask questions in their fields of ignorance. Stack Overflow has helped countless programmers and developers with programming problems, leading to the creation of the Stack Exchange: a network for topics beyond just programming. Today, StackExchange allows users to ask others questions ranging from "Can anyone suggest what technology and 3D printing material is most suitable for printing of dental models?" to "Why use 는 after 에?" It is important to note that while Stack Exchange is a great resource for answering questions, these questions come almost entirely from volunteers; people who are not obligated to answer your questions like an intern at an IT help desk. They are expecting you to do as much work as you can before asking your question.

An example of a good Question:

	Why does ++[[]][+[]]+[+[]] return the string “10”?
	This is valid and returns the string "10" in JavaScript (more examples here):
	
```
++[[]][+[]]+[+[]]
```

	Why? What is happening here?

(http://stackoverflow.com/questions/7202157/why-does-return-the-string-10)

This is a good question because it isn't something immediately apparent. Its also difficult to figure out what to search for when looking for the answer as the program only consists of brackets and plus signs, operators that are covered in Javascript documentation, but usually not to the detail that would be required to understand something like this. Since this is a good question, it recieved many answers.



It can be somewhat difficult to purposefully find bad questions for a specific topic on StackOverflow due to the truly horrible questions being culled from the site soon after they are reported by other users.
	
	C++ Need to solve this fast
	So I have this little problem. I am currently writing a slightly bigger project than this but I wanted to show my problem at as basic lvl a possible. So.. I have a simple 10-elements array if integers , and a pointer to fourth element in that array. I am filling the array with numbers 0...9 and then sort them into reverse. As you can see pointer is still showing me the value on fourth place(that's correct). So my question is. Is there a possibility, that the pointer somehow "follows" the value which it was pointing at the very beggining of code(value = 3). Sorry for bad English, if U have any questions about it , i'll try to explain. Here's a code.

```
	#include<iostream>
	#include<Windows.h>
	using namespace std;
	void main()
	{
	    int tab[10];
	    int *ptr;
	    for (int i = 0; i < 10; i++) tab[i] = i;
	    ptr = &tab[3];
	    for (int i = 0; i < 10; i++) cout << tab[i] << endl;
	    cout << *ptr << endl;
	    for (int i = 0; i < 10; i++) 
	        for (int j = 0; j < 9; j++) 
	            if (tab[j] < tab[j + 1) swap(tab[j], tab[j + 1]);
	    for (int i = 0; i < 10; i++) cout << tab[i] << endl;
	    cout << *ptr;
	    system("pause");
	} 
```


(http://stackoverflow.com/questions/37722735/c-need-to-solve-this-fast_)

This is a bad question because it could be answered if the question asker did some research on their own. It also is written in a way that assumes the answerers will do most of the leg work: they didn't post what the output is nor the expected output. It assumes that the question answerer has all the answers and will do all the work. Usually, when asking a good question, the user will make their question more general by changing variables to general statements such as "foo" and "bar," making their code look less like something that would be assigned by a ICS professor.
