# Native-SDK
Native-SDK document

```javascript
var native = {
  /**
   * @method goBack
   * @description 浏览器后退，如果向前没有history，则关闭webView
   */
   goBack: function () {}，
   
  /**
   * @method shareMessage
   * @description 调用系统分享
   * @param { Object } shareData - 分享内容数据
   */
   shareMessage: function (shareData) {}，
   
   /**
    * @method previewImage
    * @description 调用原生图片预览
    * @param {String} current - 当前显示图片的http链接
    * @param {Array} [urls] - 需要预览的图片http链接列表
    */
   previewImage: function (current, urls) {}
}

```
