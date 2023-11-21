git&gitHub 순서 
* 초기 디렉터리 생성 시 순서
1. git init 저장소 등록
2. git branch -M main
    master-> main 으로 변경
3. git remote add origin HTTPS 주소 붙여넣기
    origin == gitHub HTTP 주소 별칭
    ------------------------------------------------------
    *초기 디렉터리 생성 후 작업 진행 시 순서
 1. git add .  
     . 이란 ? 횬재 디렉터리 안 모든 파일과 폴더를 뜻함.
 2. git commit -m 'message'
    현재 스테이징된 파일의 기록명을 작성 (키워드위주로 작성)
    ex) 쇼핑몰 상품 페이지를 만들었다면?
    git commit -m 'shp man-product-end'
 3. git push origin main 
    origin== git Hub 주소
    main == Local 내컴퓨터 위치
    해석 == git Hub 에 Local 작업물을 Push 하겠다.
    --------------------------------------
    위 add->commit->push 순서 중간중간 작업 확인 리눅스 명령어
    1.git status
    Local과 Staging상태에서 작업물의 등록 상태 체크
    2.git log 
    commit과 Push 상태에서 작업물의 commit 기록과 업로드 정보체크