# Javascript-Experiment-1
var flipCoin = function(){
  if(Math.random() > 0.5){
    return true;
  } else {
    return false;
  }
}
var space = " ";
var myIntervalTimer = setInterval(function(){
  space += " ";
  if(space.length > 5000){
    space = " ";
  }
  if(flipCoin()){
    console.log('%c'+space, 'background: #9669FE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #A27AFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #AD8BFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #B89AFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #C4ABFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #D0BCFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #DDCEFF; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #E6DBFF; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #F1ECFF; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #FBF9FF; font-size: '+Math.round(Math.random()*40)+'px;');

    console.log('%c'+space, 'background: #FBF9FF; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #F1ECFF; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #E6DBFF; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #DDCEFF; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #D0BCFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #C4ABFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #B89AFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #AD8BFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #A27AFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #9669FE; font-size: '+Math.round(Math.random()*40)+'px;');

  } else {
    console.log('%c'+space, 'background: #01FCEF; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #1FFEF3; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #5FFEF7; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #74FEF8; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #92FEF9; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #A5FEFA; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #B5FFFC; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #CEFFFD; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #E1FFFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #F2FFFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #FDFFFF; font-size: '+Math.round(Math.random()*40)+'px;');

    console.log('%c'+space, 'background: #FDFFFF; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #F2FFFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #E1FFFE; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #CEFFFD; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #B5FFFC; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #A5FEFA; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #92FEF9; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #74FEF8; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #5FFEF7; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #1FFEF3; font-size: '+Math.round(Math.random()*40)+'px;');
    console.log('%c'+space, 'background: #01FCEF; font-size: '+Math.round(Math.random()*40)+'px;');

  }
}, 10);
 
setTimeout(function(){
  clearInterval(myIntervalTimer);
}, 1000 * 10);
