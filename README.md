beta - micro framework css/scss thinkframework
0.0.1


//text
tu-text-{} text 10-12-14-15-16-18-30


//colors
$thinkPrimary: #FF026C;
$thinkPrimaryBlue: #1E90FF;
$thinkBorder: #BDBDBD;
$thinkContent: #828282;
$thinkWarning: #ff1212;
$thinkInfo: #FAB170;
$thinkSuccess: #72fd37;

tu--{properties}
tu--success - green color
tu-bg-success - green background

//width
tu-w-{properies) -0 -5 -10 ... 100;

tu-full-width - full width
tu-fz - full width and full height (vh,vw)
tu-fw - full height - %

tu-d-flex - display flex
tu-d-m-flex - mobile display flex
tu-d-block - display block
tu-d-m-block - mobile display block
...
tu-jc-s   justify-content: flex-start;
tu-jc-c   justify-content: center;
tu-jc-e   justify-content: flex-end;
tu-jc-sb  justify-content: space-between;
tu-jc-sa  justify-content: space-around;
tu-ai-s   align-items: flex-start;
tu-ai-c   align-items: center;
tu-ai-e   align-items: flex-end;

tu-direction-row   row
tu-direction-m-row mobile row

tu-direction-col  column
tu-direction-m-col mobile column


//buttons
{
tu-btn-primary
tu-btn-primary-blue
..
}

tu-btn-{} background btn
tu-btn-o-{} outline btn

//padding
{properies - 4-6-8-10-12-14-16-18-20-22-24-26-28-30]
tu-pt-  padding top
tu-pl - padding left
tu-pb - padding bottom
tu-pr - padding right

//margin
{properies - 4-6-8-10-12-14-16-18-20-22-24-26-28-30]
tu-mt - margin top
tu-ml - margin left
tu-mb - margin bottom
tu-mr - margin right


//container

.tu-container {
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;

  @media (min-width: 576px) {
    .tu-container {
      max-width: 540px;
    }
  }

  @media (min-width: 768px) {
    .tu-container {
      max-width: 720px;
    }
  }

  @media (min-width: 992px) {
    .tu-container {
      max-width: 900px;
    }
  }

  @media (min-width: 1200px) {
    .tu-container {
      max-width: 1300px;
    }
  }

  @media (min-width: 1500px) {
    .tu-container {
      max-width: 1500px;
    }
  }
}
