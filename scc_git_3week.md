# 3주차 Git 수업에서 배운 것

## PR(Pull Request)
```
반영하기 전 요청하여 리뷰하고 반영하는 것!

1단계. 누가 이 작업 할 것인지 정한다. - Issue 
2단계. 각자 맡은 것을 작업한다. - Branch 
3단계. 각자 작업을 프로젝트에 합친다. - merge 
👉 (경우에 따라). 작업한 내용을 리뷰하고 최종적으로 프로젝트에 반영한다. - PR 후 merge
```

## Commit 관리하기!
- 최신의 commit을 수정하기 amend
- 어떤 내용을 되돌렸는지 새로운 commit을 남기고 되돌리기 revert
- reset (리셋)은 commit 했던 작업내역을 말 그대로 리셋시키는 것입니다.
  . soft/mixed/hard 
- 프로젝트의 변경사항을 임시적으로 보관 stash

## 협업하기
- commit 메세지 작성하는 규칙은 **commit 메시지 컨벤션(commit message convention)**!
- 👀 좋은 commit 메시지, 단위로 작성하게 되면
    - 어떤 작업을 했는지 commit history (commit log)만 보고 알 수 있다
    - 버그를 찾을 때와 코드 고치기 쉽다
    - 다른 사람이 코드를 리뷰할 때 편하다  

- `.gitignore` : 공유하거나 공개되면 안되는 나만의 설정 파일, API key 정보를 Git이 무시할 수 있도록, 없는 척하는 설정. 무시할 파일/폴더 이름을 `.gitignore` 파일에 적는다. 
- `README.md` : 프로젝트 안내글을 적어둔다. markdown(md) 형식을 따르는 텍스트파일

## Github 에서 정보 나누기
- Github 프로필 소개 페이지 작성, Github 페이지 만들기 를 해보았죠!
- 오픈소스(Open source)란 누구나 프로젝트를 사용하고, 수정하고, 배포할 수 있는 프로젝트 의미. 라이센스 지켜준다(必)
  많은 사람들이 프로젝트에 **컨트리뷰션(contribution, 기여) 하면서 발전시켜나가는 것!**
