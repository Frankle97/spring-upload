스프링에서는 **MultipartFile**을 이용하여 손쉽게 파일 업로드가 가능하다.
실무에서는 오리지널 파일 이름과 고유한 저장 이름을 구분하여 저장해야 한다. => 중복방지
파일을 다운로드 할 땐, Http Header에 Content Disposition, attachment; filename 포맷이 규약
코드 레벨에서 Resource 객체 활용
UriUtils.encode 유틸로 편리하게 인코딩 가능