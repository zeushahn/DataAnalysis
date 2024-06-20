# DataAnalysis
파이썬(Python) 이해와 빅데이터분석 실무
일자 : 2024-06-17 ~ 2024-07-18

연락처 : kennysy@naver.com


## JSON
    https://raw.githubusercontent.com/naver/naver-openapi-guide/draft/naver-openapi-swagger.json

### Driver
    from selenium import webdriver
    from selenium.webdriver.chrome.service import Service
    from webdriver_manager.chrome import ChromeDriverManager
    from selenium.webdriver.common.by import By

### Connection
    # Chrome Browser와 Chrom Driver 연결
    chrome_options = webdriver.ChromeOptions()
    driver = webdriver.Chrome(
      service=Service(ChromeDriverManager().install()),
      options=chrome_options
    )
    driver.get("http://www.opinet.co.kr/searRgSelect.do")
