# KLASS HELPER

## 변수명 default utf-8 인코딩 요망
### <로그인> /login

#### 입력 <br>
학번      id (string)<br>
비밀번호   pw (string)<br>
#### 출력<br>
성공 1 , 실패 0<br>

### <게시판> /board

#### 입력 <br>
학번 id (string)<br>
#### 출력<br>
강의코드 class_code (string)<br>
강의이름 calss_name (string)<br>
강사이름 instructor (string)<br>

### <게시판 개별> /getpostlist

#### 입력 <br>
강의코드 class_code (string)<br>
#### 출력<br>
게시물 제목 title (string)<br>
게시물 내용 content (string)<br>
작성자 author_id (string)<br>
작성시간 create_date (date) or (string)<br>
조회수 hit (int)

### <과제/인강 정보 모두 가져오기> /getAllWorks Post

#### 입력 <br>
학번      id (string)<br>
비밀번호   pw (string)<br>
#### 출력<br>


### 
과제종류(0=과제 1=인강) workType int 

과제코드 workCode string

과제과목 workCourse string

과제제목 workTitle string

과제생성시간(yyyy-MM-dd hh:mm:ss) workCreateTime string

과제종료시간(yyyy-MM-dd hh:mm:ss) workFinishTime string

제출여부(0=미제출 1=제출)(사이버강의는 수강시간이 권장시간 넘었을때 제출로 판정) isSubmit int
