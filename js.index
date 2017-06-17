$('button').on('click', function() {
    // 取得體重的input
    var w = $('#weight').val()
        // 取得身體的input
    var h = $('#height').val()
        // 將取得的體重轉成數字
    w = Number(w)
        // 將取得的身高轉成數字並且轉換成公尺單位
    h = Number(h) 
        // 計算 h 的平方
    hh = h * h /10000
        // 計算 bmi
    bmi = w / hh
    newbmi = ( bmi.toFixed(2))
        // 將計算結束顯示在 id=result 的元件上
    idealwM = (h-80) * 0.7
    newM =(idealwM.toFixed(2))
    idealwF = (h-70) * 0.6
    newF =(idealwF.toFixed(2))
    $('#result-1').val(newM)
    $('#result-2').val(newF)
    $('#result').val(newbmi)
})
$('#male').on('click', function() {
    // 取得體重的input
    var w = $('#weight').val()
        // 取得身體的input
    var h = $('#height').val()
        // 將取得的體重轉成數字
    w = Number(w)
        // 將取得的身高轉成數字並且轉換成公尺單位
    h = Number(h) 
        // 計算 h 的平方
    hh = h * h /10000
        // 計算 bmi
    idealwM = (h-80) * 0.7
    M = (w - idealwM )*100 / idealwM
    newM =(M.toFixed(2))
     $('#result-3').val(newM)
})
$('#female').on('click', function() {
    // 取得體重的input
    var w = $('#weight').val()
        // 取得身體的input
    var h = $('#height').val()
        // 將取得的體重轉成數字
    w = Number(w)
        // 將取得的身高轉成數字並且轉換成公尺單位
    h = Number(h) 
        // 計算 h 的平方
    hh = h * h /10000
        // 計算 bmi
    idealwF = (h-70) * 0.6
    F = (w - idealwF )*100 / idealwF
    newF =(F.toFixed(2))
     $('#result-3').val(newF)
})
$('#female').on('click', function() {
    // 取得體重的input
    var w = $('#weight').val()
        // 取得身體的input
    var h = $('#height').val()
        // 將取得的體重轉成數字
    w = Number(w)
        // 將取得的身高轉成數字並且轉換成公尺單位
    h = Number(h) 
        // 計算 h 的平方
    hh = h * h /10000
        // 計算 bmi
    idealwF = (h-70) * 0.6
    F = (w - idealwF )*100 / idealwF
    newF =(F.toFixed(2))
     $('#result-3').val(newF)
})
