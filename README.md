# Nestjs-Starter

## 설치
### Nestjs Client
> `npm i -g @nestjs/cli`

## 프로젝트 생성
### 생성 명령어
> `nest new [프로젝트 명]`

### 기본 dependencies
> reflect-metadata: 데코레이터(애노테이션) 사용을 위한 dependency  
> rimraf: Node 에서 `rm -rf` 명령어 사용을 위한 dependency  
> rxjs: RxJS는 이벤트 스트림을 Observable 이라는 객체로 표현한 후 비동기 이벤트 기반의 프로그램 작성을 돕는다.  
> 

### 기본 Setting
> IntelliJ 에서 Cmd + Shift + O 로 Import 시에 Double Quotes 를 Single Quote 로 변경하기: 
> Preferences -> Editor -> Code Style -> TypeScript -> Tab 'Punctuation' -> Use single quotes always 로 변경  
> Preferences -> Editor -> Code Style -> TypeScript -> Tab 'Tabs and Indents' -> Use Tab character 에 체크   
> Preferences -> Editor -> Code Style -> TypeScript -> Tab 'Wrapping and Braces' -> Simple methods in one line 체크  
>
> .eslintrc.js 에서 rule 에 .prettierrc 파일 경고 끄기 설정   
> ```
> rules: {
>   'prettier/prettier': 0,
>   ...
> }
> ```
