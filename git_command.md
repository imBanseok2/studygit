| 💡 Git 관련 명령어를 한눈에 파악합니다. |
| -------------------------------------- |

**1.basic**

```bash
# 작성자 이름, 메일 등록 (최초 1번만 실행)
git config --global user.name "github username"
git config --global user.email "github email"

# config 정보 출력
git config --global --list

# 일반 폴더 -> 로컬 저장소
git init

# 버전 상태 출력
git status

# Working Directory -> Staging Area
git add [File]
git add .  # 모든 파일 add

# Staging Area -> Commits
git commit -m "commit message"

# commits 목록 출력
git log
git log --oneline  # 한줄로 보기 옵션
git log -p  # 커밋마다 차이 보기 옵션
```



