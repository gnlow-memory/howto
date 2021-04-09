# howto
Collection of instructions, for me
## Git
- [GitHub SSH key 생성](https://syung05.tistory.com/20)
## Svelte
### Svelte + TypeScript
- https://codechips.me/how-to-use-typescript-with-svelte/
- https://github.com/sveltejs/language-tools/issues/161
## TypeScript
- [Decorators](https://coryrylan.com/blog/introduction-to-typescript-property-decorators)
## Unity
### Unity + VSCode
- [VS Code로 유니티 개발하기](https://www.androidhuman.com/2020-09-14-unity_with_vscode)
- [vs code로 작업시 intellisense가 안될때](https://velog.io/@ww9986/unity-vs-code%EB%A1%9C-%EC%9E%91%EC%97%85%EC%8B%9C-intellisense%EA%B0%80-%EC%95%88%EB%90%A0%EB%95%8C)
---
#### 요약 (Windows)
1. VSCode Extension `ms-dotnettools.csharp` 설치
2. `.NET Core SDK`가 없으면 설치하라고 주소까지 띄워줌 (Extension v1.23.9 기준 SDK는 v5.0.202)
3. `.NET Framework 4.7.1`까지 설치
4. 리부팅 (안 하면 VSCode가 dotnet을 못 찾더라..)
5. `Unity > Edit > Preferences > External Tools > External Script Editor`를 `Visual Studio Code`로 변경
6. Unity > Assets > Open C# Project
