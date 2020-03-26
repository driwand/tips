<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/FxL5qM0.jpg" alt="Bot logo"></a>
</p>

<h3 align="center">Tips</h3>

<div align="center">

</div>

---

<p align="center"> Random things One repo. 
    <br> 
</p>

## 📝 Table of Contents

- [Welcome!](#Welcome)
- [Git](#git)
- [WSL](#wsl)
- [Clion](#clion)
- [Linux](#linux)

## Git <a name = "git"></a>

**Change the editor of git to vs code:**

```
git config --global core.editor "code --wait"
```

**Store credential:**
```
git config --global credential.helper store
```

## WSL <a name = "wsl"></a>

## Clion <a name = "clion"></a>

## Linux <a name = "linux"></a>

**Add suffix to all files in a directory:**

```
for file in $(find . -type f -name "*.[filetype]")
do
  mv "$file" "${file%}[suffix].[filetype]"
done
```
