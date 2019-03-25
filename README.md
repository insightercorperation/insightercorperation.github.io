# Insighter의 기술 블로그 입니다.

> 카카오 기술블로그를 기반으로 제작하였습니다.

> 주의: [GitHub Pages](https://pages.github.com/)와 [Jekyll](https://jekyllrb.com/)에 대해서 충분히 숙지할 것.  
> 주의: [Collaborating on projects using issues and pull requests](https://help.github.com/categories/collaborating-on-projects-using-issues-and-pull-requests/)을 정독.


### 설치

- push 권한이 있을 경우

1. git fetch or pull or clone
2. [Jekyll](https://jekyllrb.com/) 설치

```console
$ git clone git@github.com:insightercorperation/insightercorperation.github.io.git
$ cd insightercorperation.github.io
$ bundle install
```

- push 권한이 없을 경우

1. [인사이터 깃헙](https://github.com/insightercorperation/insightercorperation.github.io) 에서 `Fork` 버튼 클릭하고,
2. 포크 저장소 계정(maybe 개인 계정) 선택
3. git fetch or pull or clone
4. 포크 설정 [Configuring a remote for a fork](https://help.github.com/articles/configuring-a-remote-for-a-fork/)
5. 포크 동기화 [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)
6. [Jekyll](https://jekyllrb.com/) 설치

```console
$ git clone git@github.com:YOUR_GITHUB_ACCOUNT/insightercorperation.github.io.git
$ cd insightercorperation.github.io
$ git remote add upstream git@github.com:insightercorperation/insightercorperation.github.io.git
$ git fetch upstream
$ git checkout master
$ git merge upstream/master
$ bundle install
```

### 실행(로컬)

```
$ bundle exec jekyll serve
$ open http://localhost:4000
```

### 배포(발행)

- push 권한이 있을 경우

```
$ git commit -m 'Write commit message'
$ git push origin master
```

- push 권한이 없을 경우

1. Fork 동기화 [Syncing a fork](https://help.github.com/articles/syncing-a-fork/)
2. Pull Request 보내기 [Creating a pull request](https://help.github.com/articles/creating-a-pull-request/)
