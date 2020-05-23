이건 달이야 

진짜 달이야 근데 반경은 5M

색깔은 빨간맛

1. 새로운 브랜치 DD 생성
2. MOON 추가 및 반영
3. 원격 저장소 origin DD 에 밀어넣기(git push -u origin DD) upstream 유의 
4. GitHub에서 PR 생성
5. PR을 통해 리뷰 및 수정사항 남기고
6. 혼자 답하고
7. 로컬 DD에서 수정 및 반영 후에 원격 저장소에 Push (이때 PR 화면에서 commit이 추가된 것을 확인)

그 후 GitHub에서 PR Merge로 마무리

마지막으로 local master 브랜치에서 remote 의 master 브랜치를 땡겨와서 최신화 (git pull)