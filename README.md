# fuck-xprintidle

Thank [xprintidle](https://github.com/g0hl1n/xprintidle), but fuck [xprintidle](https://github.com/g0hl1n/xprintidle)! I don't want to install the xprintidle apt package!

I am a post-00s generation and I am now tired of compiling and installing APT packages.

Especially just to read the damn "user's time without operating the keyboard and mouse" from X11

I don't think it's worth it for me to install a deb package, which is: [xprintidle](https://github.com/g0hl1n/xprintidle )

Especially when you need compatibility and deployment, when others (especially other developers) know that you have created a dependency that requires the apt command to install due to this small requirement, they will feel that your code is like dog poop.

Returning to the main topic.

I use DeepSeekR1 and [xprintidle](https://github.com/g0hl1n/xprintidle )The author's code has written a Python script that implements [xprintidle](https://github.com/g0hl1n/xprintidle) Same functionality (except for no fixes for old version X services).

And when it interacts with X11, it doesn't use the Python package xlib, yes, I want 0 dependencies.

It works well on my computer! And it's ready to use out of the box, without the need to install any dependencies.

<img width="1498" height="941" alt="image" src="https://github.com/user-attachments/assets/f303979c-bf6b-4aae-adeb-92a84e3d89ac" />

I have conducted preliminary tests using the following command. You can try it. When you operate the keyboard or mouse, the printing time will decrease. If you do not operate for a long time, the time will increase.

```bash
while true;  do python3 xprintidle.py -H;  sleep 2;  done
```

# Quick use

```
# Human-readable print
python3 xprintidle.py -H
```

```
# unit millisecond
python3 xprintidle.py
```

Finally,

Thank you [xprintidle](https://github.com/g0hl1n/xprintidle)The author, but damn it [xprintidle](https://github.com/g0hl1n/xprintidle)
