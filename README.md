## 새 Repo 생성

깃허브에서 새 레포를 만들어준다.

![New Repo](https://github.com/j1mmyson/j1mmyson.github.io/blob/master/assets/img/posts/github/deployProject/create_repo.PNG?raw=true){: height="250px"}

## Repo에 내 프로젝트 푸시

1. `$ git clone https://github.com/userName/RepoName.git`
2. `$ cd RepoName`
3. `$ touch index.html` 혹은 에디터 등으로 프로젝트파일 생성
4. `$ git add .` & `$ git commit -m "commit message"`
5. `$ git push origin main`

## gh-pages 브랜치 생성

깃허브 페이지에서도 아래와 같이 간단하게 새 브랜치를 딸 수 있다.

![New branch](https://github.com/j1mmyson/j1mmyson.github.io/blob/master/assets/img/posts/github/deployProject/create_branch.PNG?raw=true){: height="250px"}

## Repo/settings

프로젝트 레포의 `settings`에 들어가 `GitHub Pages`를 확인해보자.<br>
아마 `gh-pages`를 따게되면 자동으로 아래처럼 설정되어있을 것이다.<br>
보면 `Your site is published at ~~~` , 내 플젝이 해당 링크에 배포되었다는 메세지를 확인할 수 있다.
<br>
![gh-pages](https://github.com/j1mmyson/j1mmyson.github.io/blob/master/assets/img/posts/github/deployProject/gh-pages.PNG?raw=true){: height="350px"}

## Deploy Success!

해당 링크에서 내 프로젝트가 잘 배포된 것을 확인할 수 있다.

![Success](https://github.com/j1mmyson/j1mmyson.github.io/blob/master/assets/img/posts/github/deployProject/success.PNG?raw=true){: height="400px"}
