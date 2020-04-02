선거구 geojson
============

우리나라에는 지역을 구분하는 법정동과 행정동을 기준으로 나누고 있습니다. (이번에 알게 되었습니다.)
- **행정동**: 법덩동을 행정상으로 관할하는 **행정기관(읍면동) 명칭**과 동일
- **법정동**: **공부상의 법정주소**로서 문서에 표기되거나 주소에 사용

선거구 지역획정에는 행정동을 기준으로 분할하고 있습니다.

이 자료는 아래 출처에서 데이터를 가져와 작성하고 있습니다.


## 자료 출처
- [공공데이터포털 중앙선거관리위원회 코드정보](https://www.data.go.kr/dataset/15000897/openapi.do)
- [대한민국 행정동 경계(admdongkor)](https://github.com/vuski/admdongkor)


## 20200415_2 자료 설명
### 2020년 4월 국회의원 선거
- sgId: "20200415" // 선거 코드
- sgTypecode: "2" // 선거 종류 (국회의원 선거)
- sOrder: *.geojson // 선거구 코드
- sdName: // 시도 이름
- sggName: // 선거구명

### 서울특별시
<table>
    <tr>
        <th>코드</th>
        <th>선거구</th>
        <th>구시군</th>
        <th>읍면동</th>
    </tr>
    <tr>
        <th>1</th>
        <th>종로구</th>
        <td>종로구</td>
        <td>청운효자동, 사직동, 삼청동, 부암동, 평창동, 무악동, 교남동, 가회동, 종로1·2·3·4가동, 종로5·6가동, <br>이화동, 혜화동, 창신제1동, 창신제2동, 창신제3동, 숭인제1동, 숭인제2동
        </td>
    </tr>
    <tr>
        <th>2</th>
        <th>중구성동구갑</th>
        <td rowspan="2">성동구</td>
        <td>왕십리제2동, 왕십리도선동, 마장동, 사근동, 행당제1동, 행당제2동, 응봉동, <br>성수1가제1동, 성수1가제2동, 성수2가제1동, 성수2가제3동, 송정동, 용답동</td>
    </tr>
    <tr>
        <th rowspan="2">3</th>
        <th rowspan="2">중구성동구을</th>
        <td>금호1가동, 금호2·3가동, 금호4가동, 옥수동</td>
    </tr>
    <tr>
        <td>중구</td>
        <td>소공동, 회현동, 명동, 필동, 장충동, 광희동, 을지로동, 신당동, 다산동, 약수동, 청구동, <br>신당제5동, 동화동, 황학동, 중림동</td>
    </tr>
    <tr>
        <th>4</th>
        <th>용산구</th>
        <td>용산구</td>
        <td>후암동, 용산2가동, 남영동, 청파동, 원효로제1동, 원효로제2동, 효창동, 용문동, 한강로동, <br>이촌제1동, 이촌제2동, 이태원제1동, 이태원제2동, 한남동, 서빙고동, 보광동</td>
    </tr>
    <tr>
        <th>5</th>
        <th>광진구갑</th>
        <td rowspan="2">광진구</td>
        <td>군자동, 중곡제1동, 중곡제2동, 중곡제3동, 중곡제4동, 능동, 광장동, 구의제2동</td>
    </tr>
    <tr>
        <th>6</th>
        <th>광진구을</th>
        <td>화양동, 자양제1동, 자양제2동, 자양제3동, 자양제4동, 구의제1동, 구의제3동</td>
    </tr>
    <tr>
        <th>7</th>
        <th>동대문구갑</th>
        <td rowspan="2">동대문구</td>
        <td>용신동, 제기동, 청량리동, 회기동, 휘경제1동, 휘경제2동, 이문제1동, 이문제2동</td>
    </tr>
    <tr>
        <th>8</th>
        <th>동대문구을</th>
        <td>전농제1동, 전농제2동, 답십리제1동, 답십리제2동, 장안제1동, 장안제2동</td>
    </tr>
    <tr>
        <th>9</th>
        <th>중랑구갑</th>
        <td rowspan="2">중랑구</td>
        <td>면목제2동, 면목제4동, 면목제5동, 면목본동, 면목제7동, 면목제3·8동, 상봉제2동, 망우제3동</td>
    </tr>
    <tr>
        <th>10</th>
        <th>중랑구을</th>
        <td>상봉제1동, 중화제1동, 중화제2동, 묵제1동, 묵제2동, 망우본동, 신내제1동, 신내제2동</td>
    </tr>
    <tr>
        <th>11</th>
        <th>성북구갑</th>
        <td rowspan="2">성북구</td>
        <td>성북동, 삼선동, 동선동, 돈암제2동, 안암동, 보문동, 정릉제1동, 정릉제2동, 정릉제3동, 정릉제4동, 길음제1동</td>
    </tr>
    <tr>
        <th>12</th>
        <th>성북구을</th>
        <td>돈암제1동, 길음제2동, 종암동, 월곡제1동, 월곡제2동, 장위제1동, 장위제2동, 장위제3동, 석관동</td>
    </tr>
    <tr>
        <th>13</th>
        <th>강북구갑</th>
        <td rowspan="2">강북구</td>
        <td>번1동, 번2동, 수유1동, 수유2동, 수유3동, 우이동, 인수동</td>
    </tr>
    <tr>
        <th>14</th>
        <th>강북구을</th>
        <td>삼양동, 미아동, 송중동, 송천동, 삼각산동, 번3동</td>
    </tr>
    <tr>
        <th>15</th>
        <th>도봉구갑</th>
        <td rowspan="2">도봉구</td>
        <td>창제1동, 창제2동, 창제3동, 창제4동, 창제5동, 쌍문제1동, 쌍문제3동</td>
    </tr>
    <tr>
        <th>16</th>
        <th>도봉구을</th>
        <td>도봉제1동, 도봉제2동, 쌍문제2동, 쌍문제4동, 방학제1동, 방학제2동, 방학제3동</td>
    </tr>
    <tr>
        <th>17</th>
        <th>노원구갑</th>
        <td rowspan="3">노원구</td>
        <td>월계1동, 월계2동, 월계3동, 공릉1동, 공릉2동</td>
    </tr>
    <tr>
        <th>18</th>
        <th>노원구을</th>
        <td>하계1동, 하계2동, 중계본동, 중계1동, 중계4동, 중계2·3동, 상계6·7동</td>
    </tr>
    <tr>
        <th>19</th>
        <th>노원구병</th>
        <td>상계1동, 상계2동, 상계3·4동, 상계5동, 상계8동, 상계9동, 상계10동</td>
    </tr>
    <tr>
        <th>20</th>
        <th>은평구갑</th>
        <td rowspan="2">은평구</td>
        <td>녹번동, 응암제1동, 응암제2동, 응암제3동, 역촌동, 신사제1동, 신사제2동, 증산동, 수색동</td>
    </tr>
    <tr>
        <th>21</th>
        <th>은평구을</th>
        <td>불광제1동, 불광제2동, 갈현제1동, 갈현제2동, 구산동, 대조동, 진관동</td>
    </tr>
    <tr>
        <th>22</th>
        <th>서대문구갑</th>
        <td rowspan="2">서대문구</td>
        <td>천연동, 북아현동, 충현동, 신촌동, 연희동, 홍제제1동, 홍제제2동</td>
    </tr>
    <tr>
        <th>23</th>
        <th>서대문구을</th>
        <td>홍제제3동, 홍은제1동, 홍은제2동, 남가좌제1동, 남가좌제2동, 북가좌제1동, 북가좌제2동</td>
    </tr>
    <tr>
        <th>24</th>
        <th>마포구갑</th>
        <td rowspan="2">마포구</td>
        <td>아현동, 공덕동, 도화동, 용강동, 대흥동, 염리동, 신수동</td>
    </tr>
    <tr>
        <th>25</th>
        <th>마포구을</th>
        <td>서강동, 서교동, 합정동, 망원제1동, 망원제2동, 연남동, 성산제1동, 성산제2동, 상암동</td>
    </tr>
    <tr>
        <th>26</th>
        <th>양천구갑</th>
        <td rowspan="2">양천구</td>
        <td>목1동, 목2동, 목3동, 목4동, 목5동, 신정1동, 신정2동, 신정6동, 신정7동</td>
    </tr>
    <tr>
        <th>27</th>
        <th>양천구을</th>
        <td>신월1동, 신월2동, 신월3동, 신월4동, 신월5동, 신월6동, 신월7동, 신정3동, 신정4동</td>
    </tr>
    <tr>
        <th>28</th>
        <th>강서구갑</th>
        <td rowspan="3">강서구</td>
        <td>화곡제1동, 화곡제2동, 화곡제3동, 화곡제8동, 발산제1동, 우장산동</td>
    </tr>
    <tr>
        <th>29</th>
        <th>강서구을</th>
        <td>등촌제3동, 가양제1동, 가양제2동, 공항동, 방화제1동, 방화제2동, 방화제3동</td>
    </tr>
    <tr>
        <th>30</th>
        <th>강서구병</th>
        <td>염창동, 등촌제1동, 등촌제2동, 화곡제4동, 화곡본동, 화곡제6동, 가양제3동</td>
    </tr>
    <tr>
        <th>31</th>
        <th>구로구갑</th>
        <td rowspan="2">구로구</td>
        <td>고척제1동, 고척제2동, 개봉제1동, 개봉제2동, 개봉제3동, 오류제1동, 오류제2동, 수궁동, 항동</td>
    </tr>
    <tr>
        <th>32</th>
        <th>구로구을</th>
        <td>신도림동, 구로제1동, 구로제2동, 구로제3동, 구로제4동, 구로제5동, 가리봉동</td>
    </tr>
    <tr>
        <th>33</th>
        <th>금천구</th>
        <td>금천구</td>
        <td>가산동, 독산제1동, 독산제2동, 독산제3동, 독산제4동, 시흥제1동, 시흥제2동, 시흥제3동, 시흥제4동, 시흥제5동</td>
    </tr>
    <tr>
        <th>34</th>
        <th>영등포구갑</th>
        <td rowspan="2">영등포구</td>
        <td>영등포본동, 영등포동, 당산제1동, 당산제2동, 도림동, 문래동, 양평제1동, 양평제2동, 신길제3동</td>
    </tr>
    <tr>
        <th>35</th>
        <th>영등포구을</th>
        <td>여의동, 신길제1동, 신길제4동, 신길제5동, 신길제6동, 신길제7동, 대림제1동, 대림제2동, 대림제3동</td>
    </tr>
    <tr>
        <th>36</th>
        <th>동작구갑</th>
        <td rowspan="2">동작구</td>
        <td>노량진제1동, 노량진제2동, 상도제2동, 상도제3동, 상도제4동, 대방동, 신대방제1동, 신대방제2동</td>
    </tr>
    <tr>
        <th>37</th>
        <th>동작구을</th>
        <td>상도제1동, 흑석동, 사당제1동, 사당제2동, 사당제3동, 사당제4동, 사당제5동</td>
    </tr>
    <tr>
        <th>38</th>
        <th>관악구갑</th>
        <td rowspan="2">관악구</td>
        <td>보라매동, 청림동, 성현동, 행운동, 낙성대동, 청룡동, 은천동, 중앙동, 인헌동, 남현동, 신림동</td>
    </tr>
    <tr>
        <th>39</th>
        <th>관악구을</th>
        <td>서원동, 신원동, 서림동, 신사동, 난향동, 조원동, 대학동, 삼성동, 미성동, 난곡동</td>
    </tr>
    <tr>
        <th>40</th>
        <th>서초구갑</th>
        <td rowspan="2">서초구</td>
        <td>잠원동, 반포본동, 반포1동, 반포2동, 반포3동, 반포4동, 방배본동, 방배1동, 방배4동</td>
    </tr>
    <tr>
        <th>41</th>
        <th>서초구을</th>
        <td>서초1동, 서초2동, 서초3동, 서초4동, 방배2동, 방배3동, 양재1동, 양재2동, 내곡동</td>
    </tr>
    <tr>
        <th>42</th>
        <th>강남구갑</th>
        <td rowspan="3">강남구</td>
        <td>신사동, 논현1동, 논현2동, 압구정동, 청담동, 역삼1동, 역삼2동</td>
    </tr>
    <tr>
        <th>43</th>
        <th>강남구을</th>
        <td>개포1동, 개포2동, 개포4동, 세곡동, 일원본동, 일원1동, 일원2동, 수서동</td>
    </tr>
    <tr>
        <th>44</th>
        <th>강남구병</th>
        <td>삼성1동, 삼성2동, 대치1동, 대치2동, 대치4동, 도곡1동, 도곡2동</td>
    </tr>
    <tr>
        <th>45</th>
        <th>송파구갑</th>
        <td rowspan="3">송파구</td>
        <td>풍납1동, 풍납2동, 방이1동, 방이2동, 오륜동, 송파1동, 송파2동, 잠실4동, 잠실6동</td>
    </tr>
    <tr>
        <th>46</th>
        <th>송파구을</th>
        <td>석촌동, 삼전동, 가락1동, 문정2동, 잠실본동, 잠실2동, 잠실3동, 잠실7동</td>
    </tr>
    <tr>
        <th>47</th>
        <th>송파구병</th>
        <td>거여1동, 거여2동, 마천1동, 마천2동, 오금동, 가락본동, 가락2동, 문정1동, 장지동, 위례동</td>
    </tr>
    <tr>
        <th>48</th>
        <th>강동구갑</th>
        <td rowspan="2">강동구</td>
        <td>강일동, 상일동, 명일제1동, 명일제2동, 고덕제1동, 고덕제2동, 암사제1동, 암사제2동, 암사제3동, 길동</td>
    </tr>
    <tr>
        <th>49</th>
        <th>강동구을</th>
        <td>천호제1동, 천호제2동, 천호제3동, 성내제1동, 성내제2동, 성내제3동, 둔촌제1동, 둔촌제2동</td>
    </tr>
</table>

##### 작업시 참고사항)
+ 성수2가1동과 성수2가3동은 있는데, 성수2가2동은 없다. (cf. 자양제4동)
+ 성북구에는 성북동이 있다.
+ 구로구 항동은 2020년 1월 1일 새로 생긴 동이다. (cf. 오류제2동)
