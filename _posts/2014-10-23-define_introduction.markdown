---
layout: post
title:  "define introduction"
date:   2014-10-23 15:18:59
categories: jekyll update
---

#define introduction

<p>sample_1.c</p>

<pre><code>
#include<stdio.h>
#define M (y * y + 3 * y)

int main()
{
        int s, y;

        printf("input a number: ");

        scanf("%d", &y);

        s = 3 * M + 4 * M + 5 * M;

        printf("s = %d\n", s);

        return 0;
}
</pre></code>

###define  undef

<p>sample_2.c

<pre><code>
##define PI 3.14159

int main(){
    /* ... */

    return 0;
}

##undef PI
f1(){
    /* ... */
}
</pre></code>

