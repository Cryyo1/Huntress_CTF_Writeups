# Challenge 

Remember when Missouri got into hacking!?! You gotta be fast to catch this flag!

Press the Start button on the top-right to begin this challenge

# Solution 

- u have to be fast 
- seeing the link when you press capture the flag it open /capture_the_flag.html
- entering the path and viewing the page source we can find the flag

```html
<div class="container p-5">
            <div class="text-center mt-5 p-5">
                <button type="button" onclick="ctf()" class="btn btn-success"><h1>Your flag is:<br>
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  <span style="display:none">
                  flag{03e8ba07d1584c17e69ac95c341a2569}
                </span></button>
            </div>
        </div>
```