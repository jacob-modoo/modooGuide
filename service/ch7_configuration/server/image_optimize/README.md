# 이미지 최적화

## 개요
> 고용량/고화질의 업로드 이미지로 인한 서비스 속도 저하문제 해결

## 핵심목표
> 로딩 속도 최적화와 깨끗한 이미지 제공

## Content

서버상에 없는 /speed/ 폴더 경로로 url 접근 주소 변경하여, ".htaccess" 이용, "index.php"가 동작하도록 설계
1. ?width=300&height=300과 같는 요청 받음.
2. /data_new/speed/ 화일 존재여부 확인
3. 없을 경우 요청사항에 맞쳐 컨버팅 진행 (md5 첫 자리 이용하여 파일 저장 폴더 분산)
4. 이미지 출력
````image
	ob_start('ob_gzhandler');
	$fp = fopen($file, 'rb');
	fpassthru($fp);
	fclose ($fp);
````

## 작업자
> @안지환
