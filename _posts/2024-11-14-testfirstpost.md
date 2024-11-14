---
layout: post
title: "testfirstpost"
date: 2024-11-14 20:53:59 +0900
tags: [test]
---
## 내용테스트
- 이거 어떻게 작성하나요

## 구축 과정

```HTML
<html>
	<body>
		Hello! This is the first page!
		<hr>
		<h2>깃블로그 만들기</h2>
		<ol>
			<li>1단계</li>
			<ul>
				<li>username.github.io 레포지토리 생성 (pubilc, README 체크)</li>
				<li>Setting - Pages - Source - 'Deploy from a branch' 설정</li>
				<li>사이트 접속 확인하기 (https://username.github.io)</li>
				<li>git clone 후 index.html 파일 생성, 커밋, 푸시</li>
			</ul>
			<li>2단계</li>
			<ul>
				<li>Ruby 설치, 'Start Command Prompt with Ruby'에서 명령어 입력</li>
				<li>이동: <br>
					cd C:\Users\username\Documents\username.github.io
				</li>
				<li>설치: <br>
					gem install jekyll bundler<br>
					gem install webrick
				</li>
				<li>설치 확인: <br>
					ruby -v<br>
					jekyll -v<br>
					bundler -v
				</li>
				<li>Jekyll 서버 구축: <br>
					jekyll new ./<br>
					# 또는<br>
					jekyll new ./ --force
					</li>
				<li>bundle 설치: <br>
					bundle install
				</li>
				<li>서버 실행: <br>
					bundle exec jekyll serve
				</li>
				<li>포트 접속 확인<br>
				http://127.0.0.1:4000/ 또는 http://localhost:4000/ 접속 확인
				</li>
			</ul>
			<li>Jekyll 테마 적용</li>
			<ul>
				<li>테마 선택: (예시)<br>
					http://jekyllthemes.org<br>
					https://jekyllthemes.io/free<br>
					https://themes.jekyllrc.org<br>
					https://github.com/topics/jekyll-theme
				</li>
				<li>테마 적용: <br>
					https://github.com/cotes2020/jekyll-theme-chirpy<br>
					모든 파일, 폴더를 로컬 레포지토리에 복붙
				</li>
				<li>루비 프롬프트: <br>
					bundle install<br>
					bundle exec jekyll serve<br>
					서버 실행
				</li>
				<li>깃허브: <br>
					Setting - Pages - Source - Github Actions 설정<br>
					Configure 클릭<br>
					Commit changes... 클릭, 로컬에서 pull
				</li>
				<li>Node.js 설치<br>
					https://nodejs.org/en/<br>
					루비 프롬프트: <br>
					<!-- npm install -g win-node-env -->
					npm install && npm run build
				</li>
			</ul>
			<li>테마 상세설정</li>
			<ul>
				<li>.gitignore 하단 수정: <br>
					# Misc<br>
					# _sass/dist<br>
					# assets/js/dist
				</li>
				<li>_config.yml 수정: <br>
					timezone: Asia/Seoul<br>
					url: "https://username.github.io"<br>
					github:<br>
					  username: username<br>
				</li>
			</ul>
			<li>사이트 반영 확인</li>
		</ol>
	</body>
</html>	</ul>
			<li></li>
			<li></li>
		</ol>
	</body>
</html>
```
테스트내용