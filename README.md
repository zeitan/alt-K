# alt+K
Simple bash script to emulate in Linux/zsh the cmd +  K from macOS/OSX 

1. create a bash file with this content
````
echo -e '\0033\0143'
````
2. Give execution permissions (chmod +x)
3. add in your .zshrc/.zshprofile the following entry
````
bindkey -s '<code_keys>' '/path/to/your_file.sh\n'
````
You can use ```` showkey -a ```` to get the code_keys value


https://user-images.githubusercontent.com/245020/160965536-34ecff28-e917-473b-a178-721268066336.mp4



