# JSON API Project

Next.js 기반의 비정형 데이터를 구조화된 JSON으로 변환하는 API 프로젝트입니다.

## 주요 기능

- 비정형 텍스트 데이터를 구조화된 JSON으로 변환
- OpenAI GPT-4 모델 활용
- 커스터마이즈 가능한 JSON 스키마

## 시작하기

1. 저장소 클론
2. 의존성 설치: `npm install`
3. OpenAI API 키 설정: `OPENAI_API_KEY=your_api_key_here`
4. 개발 서버 실행: `npm run dev`
5. http://localhost:3000 접속

## API 사용법

`/api/json`에 POST 요청:

```
{
"data": "변환할 텍스트",
"format": {
// 원하는 JSON 스키마
}
}
```
## 기술 스택

- Next.js 14.2.4
- React 18
- OpenAI API
- Tailwind CSS
- TypeScript

## 더 알아보기

- [Next.js 문서](https://nextjs.org/docs)
- [OpenAI API 문서](https://platform.openai.com/docs/api-reference)

## 배포

[Vercel 플랫폼](https://vercel.com/new)을 통해 쉽게 배포할 수 있습니다.
