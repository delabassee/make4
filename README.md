# SJP

**Simple Java blurb... Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.**

```Java
	public static int sjp(int[] list)
	{	assert list != null && list.length > 0 : "failed precondition";

		int indexOfMin = 0;
		for(int i = 1; i < list.length; i++)
		{	if(list[i] < list[indexOfMin])
			{	indexOfMin = i;
			}
		}

		return indexOfMin;
	}
```

# News

## Jan 6th, 2017 - SJP 1.2.8-219 released ##

[Release Notes](http://oracle.com) - [Download](http://oracle.com)

## Nov 26th, 2016 - SJP Public Draft review started ##

See the Publilc Draft [here](http://oracle.com).

