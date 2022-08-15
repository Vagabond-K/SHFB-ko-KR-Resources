# Sandcastle Help File Builder의 한국어 리소스 모음

Sandcastle을 이용하여 개인용 .NET 라이브러리의 문서를 만들 때, 한국어 리소스가 없길래 만들었습니다.  
한국어 리소스를 적용하면 'Namespace'는 '네임스페이스'로, 'Class'는 '클래스'로, 'Method'는 '메서드'로 표시됩니다.  
  
현재는 Visual Studio MSDN 스타일인 VS2013 스타일만 만들어져 있습니다.  


### 사용 방법
1. C:\Program Files (x86)\EWSoftware\Sandcastle Help File Builder\Components\VS2013 경로에 ko-KR 폴더를 생성합니다.
2. conceptual_content.xml, reference_content.xml, shared_content.xml, shared_content_mshc.xml 파일을 해당 폴더에 복사합니다.
3. Sandcastle Help File Builder GUI로 프로젝트를 생성한 후, 'Presentation style'을 'VS2013'으로 설정합니다.
4. 'Help file language'는 'Korean (Korea)'로 설정합니다.
5. 빌드를 실행합니다.


### 참조 링크
- [Sandcastle Help File Builder](https://github.com/EWSoftware/SHFB)
