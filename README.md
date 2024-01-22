## <p align="center">Hey, I'm Anthony.</p>

<p align="center">
    <img src="https://readme-typing-svg.herokuapp.com?color=E22FE4&width=380&height=45&lines=Gopher;Blockchain+Enthusiast;Rustacean.&center=true"></a>
</p>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=anthonyoliai&label=Profile%20views&color=129e00&style=plastic" alt="Anthony" /> </p>

<h1 align="center"> Contributions. </h1>

<p align= "left">	
  <img  src="https://github-readme-streak-stats.herokuapp.com/?user=anthonyoliai&show_icons=true&theme=onedark" />
  <img src="https://github-readme-stats.vercel.app/api?username=anthonyoliai&show_icons=true&locale=en&theme=cobalt" alt="Anthony" />
</p>


<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://golang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> </a> <a href="https://kubernetes.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://redis.io" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/> </a> <a href="https://www.rust-lang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-plain.svg" alt="rust" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> </p>


```go
package main

import (
	"encoding/base64"
	"fmt"
	"os"
	"bufio"
	"strings"
)

func main() {
	encodedMessage := "SWYgeW91IHB1dCBhIG1pbGxpb24gbW9ua2V5cyBhdCBhIG1pbGxpb24ga2V5Ym9hcmRzLCBvbmUgb2YgdGhlbSB3aWxsIGV2ZW50dWFsbHkgd3JpdGUgYSBKYXZhIHByb2dyYW0uIFRoZSByZXN0IG9mIHRoZW0gd2lsbCB3cml0ZSBDIyBwcm9ncmFtcy4="

	fmt.Println("🔍 Decode the following message.")
	
	scanner := bufio.NewScanner(os.Stdin)
	scanner.Scan()
	userInput := strings.TrimSpace(scanner.Text())

	decodedMessage, err := decodeBase64(userInput)
	if err != nil {
		fmt.Println("Error decoding message:", err)
		return
	}

	fmt.Printf("\n🎉 Decoded Message: %s\n", decodedMessage)
}
```

## Connect with me

[![Linkedin Badge](https://img.shields.io/badge/-AnthonyOliai-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/anthony-oliai-52315118b//)](https://www.linkedin.com/in/anthony-oliai-52315118b/)
[![Gmail Badge](https://img.shields.io/badge/-anthonyoliai@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:anthonyoliai@gmail.com)](mailto:anthonyoliai@gmail.com)
