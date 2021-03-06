Ethereum: * [Curated resource for Ethreum](https://github.com/djphillyg/awesome-ethereum)

- Linux
Remove dir and all contents:
rm -rf <dir name>
  
- Vagrant
Good tutorial: https://www.youtube.com/watch?v=vBreXjkizgo

Nodemodule tip:
npm install -g depcheck
than 'npx depcheck' inside root directory

Secure project:
LavaMoat - https://github.com/LavaMoat/lavamoat
  
  

Git Commands
============

List differecens:
`git diff origin/master..HEAD`

`git show <commit hash> <comit hash>`

`git push --set-upstream origin develop`

`git reset --hard HEAD^` - descarta committs que não devem ir pro push

### Getting & Creating Projects

| Command | Description |
| ------- | ----------- |
| `git clone ssh://git@github.com/[username]/[repository-name].git` | Create a local copy of a remote repository |

### Basic Snapshotting

| Command | Description |
| ------- | ----------- |
| `git status` | Check status |
| `git add [file-name.txt]` | Add a file to the staging area |
| `git add -A` | Add all new and changed files to the staging area |
| `git commit -m "[commit message]"` | Commit changes |
| `git rm -r [file-name.txt]` | Remove a file (or folder) |

### Branching & Merging

| Command | Description |
| ------- | ----------- |
| `git branch` | List branches (the asterisk denotes the current branch) |
| `git branch -a` | List all branches (local and remote) |
| `git branch [branch name]` | Create a new branch |
| `git branch -d [branch name]` | Delete a branch |
| `git push origin --delete [branchName]` | Delete a remote branch |
| `git checkout -b [branch name]` | Create a new branch and switch to it |
| `git checkout -b [branch name] origin/[branch name]` | Clone a remote branch and switch to it |
| `git checkout [branch name]` | Switch to a branch |
| `git checkout -` | Switch to the branch last checked out |
| `git checkout -- [file-name.txt]` | Discard changes to a file |
| `git merge [branch name]` | Merge a branch into the active branch |
| `git merge [source branch] [target branch]` | Merge a branch into a target branch |
| `git stash` | Stash changes in a dirty working directory |
| `git stash clear` | Remove all stashed entries |

### Sharing & Updating Projects

| Command | Description |
| ------- | ----------- |
| `git push origin [branch name]` | Push a branch to your remote repository |
| `git push -u origin [branch name]` | Push changes to remote repository (and remember the branch) |
| `git push` | Push changes to remote repository (remembered branch) |
| `git push origin --delete [branch name]` | Delete a remote branch |
| `git pull` | Update local repository to the newest commit |
| `git pull origin [branch name]` | Pull changes from remote repository |
| `git remote add origin ssh://git@github.com/[username]/[repository-name].git` | Add a remote repository |
| `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git` | Set a repository's origin branch to SSH |

### Inspection & Comparison

| Command | Description |
| ------- | ----------- |
| `git log` | View changes |
| `git log --summary` | View changes (detailed) |
| `git diff [source branch] [target branch}` | Preview changes before merging |

### Rebase
https://www.youtube.com/watch?v=f1wnYdLEpgI

### Docker tips:
  https://typeofnan.dev/how-to-stop-all-docker-containers/
  
### Luiz dev environment
- Visual Code
- Github
- Terminator
- Metamask
- Hardhat
- Truffle
- npm
- nodejs 
- sudo apt-get install vlc (pra ver videos mp4)


 - setar no github ssh e gpg key
 
 - fazer L3150 funcionar em Ubuntu: 
   https://tutorialforlinux.com/2020/03/11/step-by-step-driver-epson-l3150-l3160-ubuntu-20-04-installation/
   Pra configurar impressora e wifi, entrar wifi direct na impressora, entrar local http://192.168.223.1/ e se for outro link, imprimir página de relatorio que nela sai a url. aí entrar em conf avançadas e configurar a rede wifi manualmente (ssid e senha). aí depois é só ir em adicionar impressora que acha a impressora e adicionar. usar aplicativo no celular pra ver config de setup da impressora, como limpar cabeçote e níverl de tinta. pq no linux é chato fazer configurar.
   
   comandos linux
   df -h (mostra espaço linux)
   df -i (mostra inodes)
   netstat -atunp (mostra todas as portas e ips )
   ps -ef (mostra todos os processos)
   top (mostra resumo do sistema, consume de memória - NI mostra prioridade e -20 é o máximo de prioridade)
   du -sh * (mostra o tamanho dos arquivos)
   crtl + r (reverse search do history)
   alt+t (reverte o que digitou)
   
   comandos docker
  docker stop $(docker ps -a -q)
   
   ### Initial code for challenges
   ```Java
   import java.util.*;

   public class MyClass {
    public static void main(String args[]) {
    String str = "123deefghhij4k555443";

    Map<String,String> map = new HashMap<String, String>();
    List<String> list = new ArrayList<String>();
    Iterator<String> it = list.iterator();
    
    while(it.hasNext()){
        String s = it.next();
    }
    
    int cont = 0;
    for(int i=0; i<cont; i++){
        
    }
    
    StringTokenizer tokenizer = new StringTokenizer(str, ",");
    while (tokenizer.hasMoreElements()) {
        tokenizer.nextToken();
    }


    }
   }
   ```

