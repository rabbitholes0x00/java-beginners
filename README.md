# README!
* Name: `Java`
* Designed by: `James Gosling` at `Sun Microsystems` (which has since been acquired by Oracle)
* First appeared: `1995`
* Developer: `Oracle`
* Paradigm: `imperative`, `generic`, `object-oriented (class-based)`, `functional`, `reflective`, `concurrent`
* Typing and types discipline: `static` and `strong`
* Package manager: `Maven`
* Total keywords in Java 17: `52`
* Official sites: `https://www.java.com/en`

## Java, Installations
Check java version by following this command `java -version` and branch u java version `sudo update-alternatives --config java` and `update-alternatives --list java` or `update-alternatives --list javac`

When java can't installed on your machine, following this commands for install `jdk` and `jre`
```zsh
sudo apt install openjdk-[TAB]-jdk
sudo apt install openjdk-[TAB]-jre
```

Create $PATH on `~/.zshrc` for Java
```zsh
export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
export PATH=$PATH:$JAVA_HOME/bin
_SILENT_JAVA_OPTIONS="$_JAVA_OPTIONS"
unset _JAVA_OPTIONS
alias java='java "$_SILENT_JAVA_OPTIONS"'
```

$PATH v2 on `~/.zshrc` for Java
```zsh
export JAVA_HOME=$(dirname $(dirname $(update-alternatives --list javac)))
```




