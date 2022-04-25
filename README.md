# dependency-cruiser
자바스크립트 프로젝트 ERD 자동화 모듈

1. npm install dependency-cruiser --save-dev
2. graphViz 설치
3. package.json -> "scripts" : {
  "명령어" : "depcruise --include-only \"^src\" --output-type dot src | dot -T svg > dependencygraph.svg"
}
3-1. 제외하고 싶은 파일이나 폴더가 있으면 --exclude 옵션을 사용하면 된다.
4. npm run 명령어
5. 프로젝트 안에 .svg 파일이 생성 확인
