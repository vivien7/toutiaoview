# toutiaoview
头条面试题，1面
头条易1面就挂了，当场挂，细细一想面试题并不难，视频挂断后，自己花了一个多小时就实现了
面试题
const obj = {
  "selector": {
    "to": {
      "toutiao": "FE coder"
    }
  },
  "target": [
    1,
    2,
    {
      "name": "byted"
    }
  ]
};
console.log(get123(obj, 'selector.to.toutiao'))
//FE coder
console.log(get123(obj, 'target[2].name'))
//byted
