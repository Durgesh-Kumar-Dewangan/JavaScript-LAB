# **Looping a triangle- Problem**
>  Write a loop that makes seven calls to console.log to output the following
>   triangle:
>   ```
>   #
>   ##
>   ###
>   ####
>   #####
>   ######
>   #######
> ```
>   It may be useful to know that you can find the length of a string by writing .length after it.
>   let abc = "abc";
>   console.log(abc.length);
>    // → 3"

```Code 1```
```bash
  for (let line = "#"; line.length < 8; line += "#")
  console.log(line);
```
```Code 2```
```bash
  for(let i='#'; i<='#######'; i = i + '#'){
  console.log(i);
  }
```
 ```Output```
```bash 
  #
  ##
  ###
  ####
  #####
  ######
  #######
```
