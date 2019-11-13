<h1>schedule-timeline</h1>


<span style="margin:0 2px"><img src="https://img.shields.io/badge/framework-vue2.6.6-brightgreen.svg" ></span>
<span style="margin:0 2px"><img src="https://img.shields.io/badge/Rendering-SSR-blue.svg" ></span>
<span style="margin:0 2px"><img src="https://img.shields.io/badge/style-sass-yellowgreen.svg" ></span>
<span style="margin:0 2px"><img src="https://img.shields.io/badge/datePicker-airbnbDatepicker-red.svg" ></span>



## Main
- Legacy 하게 작업(SSR)
- airbnb datepicker 사용


## 사용법
> Timeline
- 시간은 UTC시간입니다

```
data() {
    contents: {
      title: '타이틀1',
      content: '스케줄 내용',
      scheduleDate: [
          {
              from:  '',
              to: ''
          },
          {
              from: '',
              to: ''
          },
      ]
  },
```