# Create compressed archive

### Question:
Create the archive file **/root/local.tgz** for **/usr/local** compressed by **gzip**.

<details>
  <summary><b>Click to expand!</b></summary>

### Answer:

* The command is simple and straightforward (just remember that **-f** flag must be the last one as the file name follows it):

```
tar -cvzf /root/local.tgz /usr/local
```
  
</details>
