<template>
<div class="listContainer">
    <div class="date">
        <div class="data-item">
        <div>开始日期</div>
        <div class="block">
               <input type="datetime">
        </div>
        </div>
        <div class="data-item">
              <div>结束日期</div>
              <div class="block">
                <input type="datetime">
              </div>
        </div>
    </div>
<div id="listReport">
    <ul class="containerUl">
        
        <li>健康报告</li>
        <li>2018/12/28 10：22：34</li>
    </ul>
    <ul class="containerUl">
        <li>健康报告</li>
        <li>2018/12/28 10：22：34</li>
    </ul>
    <ul class="containerUl">
        <li>健康报告</li>
        <li>2018/12/28 10：22：34</li>
    </ul>
    <ul class="containerUl">
        <li>健康报告</li>
        <li>2018/12/28 10：22：34</li>
    </ul>
    <ul class="containerUl">
        <li>健康报告</li>
        <li>2018/12/28 10：22：34</li>
    </ul>
  </div>
   </div> 
</template>
<script>
export default {
    name:"ReportList"
}

</script>
<style lang="scss" scoped>
*{
    margin: 0;
    padding: 0;
}
.listContainer{
    width: 100%;
    height: 100%;
    .date{
        width: 90%;
        height: 50px;
        margin: 20px auto;
        display: flex;
        .data-item{
        margin-left:110px;
        display: flex;
        flex-direction: row;
        width: 50%;
        list-style: none;
        }
}
}
  #listReport{
      width: 90%;
      height: 300px;
      margin: 20px auto;
      text-align: center;
      .containerUl{
          width: 100%;
          height: 50px;
          display: flex;
          list-style: none;
          li{
              width: 100%;
              flex-direction: row;
          }
      }
  }
</style>

