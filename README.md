# react-native-image-slider
react native图片轮播

# 使用

<ImageSlider
    height={200} autoplay={true}
    images={['http://...',
    'http://...']} />
    
# 参数

 * 必有属性：
 *  images:['http://....']，图片链接数组
 * 可选属性：
 *  width: 默认100%
 *  height: 默认150
 *  autoplay: 默认false
 *  throttleDis: 滑动大于多少距离就显示下一张。默认100
 *  throttleTime: 滑动时间，快于多少就显示下一张
 *  loopDur 自动播放时，每一张的间隔时间，默认2000 (单位ms)
