# 17Media_INTERVIEW

2017 Campaign site Senior 前端工程師

現場實機考試
千分位


if(Math.ceil(num) == num) // 整数

    return num.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ",");
    
else

    return num.toString().replace(/\B(?=(\d{3})+(?=\.))/g, ",");
