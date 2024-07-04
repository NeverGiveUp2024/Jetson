:root {
    /* 1、颜色相关属性 */
    /*通常是网站或应用程序的主要颜色，用于强调重要元素或品牌标识 */
    --color-primary: #3578e5;
    /* 次要颜色，通常用于背景、边框或其他次要元素，与主要颜色形成对比*/
    --color-secondary: #ebedf0;
    /* 表示成功状态的颜色，用于显示操作成功或积极的反馈信息 */
    --color-success: #00a400;
    /* 信息性的颜色，用于显示一般信息或提示 */
    --color-info: #54c7ec;
    /* 警告状态的颜色，用于显示警告或需要注意的信息 */
    --color-warning: #ffba00;
    /* 危险状态的颜色，用于显示错误、危险或失败的状态 */
    --color-danger: #fa383e;


    /* 2、字体相关属性 */
    /* 主要字体：网页正文和标题的默认字体 */
    --main-font-family: 'Arial', sans-serif;
    /* 字体大小：设置网页上不同元素的字体大小 */
    --base-font-size: 16px;

    /* 3、间距和尺寸属性 
    边距和填充：用于控制元素之间的间距和内部填充
    宽度和高度：用于定义各种元素的宽度和高度
    */
    /* 一个基本的间距单位，用于在整个网页或应用程序中保持一致的间距大小 */
    --spacing-unit: 8px;
    /* 表示小尺寸的填充，直接使用了 --spacing-unit 的值 */
    --padding-small: var(--spacing-unit);
    /* 表示中等尺寸的填充，是 --spacing-unit 值的两倍大小 */
    --padding-medium: calc(2 * var(--spacing-unit));
    /* 表示大尺寸的填充，是 --spacing-unit 值的三倍大小 */
    --padding-large: calc(3 * var(--spacing-unit));
    /* 这是一个元素的宽度，通常用于确保该元素铺满其父容器的宽度 */
    --element-width: 100%;
    /* 这是侧边栏的宽度，用于定义侧边栏的固定宽度值 */
    --sidebar-width: 250px;

    /* 4、背景和边框属性 
    背景色和背景图像：设置网页或特定区域的背景
    边框样式和颜色：用于装饰和区分不同的页面元素
    */
    --background-color: #f0f0f0;
    --content-background-color: #ffffff;
    --border-color: #ccc;
    --border-width: 1px;
    --border-radius: 4px;

    /* 5、响应式设计属性 
    媒体查询断点：定义响应式设计的断点，
    根据不同的屏幕尺寸调整网页布局和元素样式
    */
    /* 用于响应式设计的媒体查询断点，
    表示当屏幕宽度达到或超过 768 像素时，
    特定的 CSS 样式将被应用或改变 */
    --tablet-breakpoint: 768px;
    /* 用于响应式设计的媒体查询断点，
    表示当屏幕宽度达到或超过 1024 像素时，
    特定的 CSS 样式将被应用或改变 */
    --desktop-breakpoint: 1024px;
/* eg；
@media (min-width: var(--tablet-breakpoint)) {
    .sidebar {
        display: block;
    }
}

@media (min-width: var(--desktop-breakpoint)) {
    .sidebar {
        width: 250px;
    }
} */


    /* 6、动画和过渡属性 
    过渡持续时间和延迟：
    定义元素过渡效果的持续时间和开始前的延迟时间
    动画效果：设置网页中动态元素的动画效果和速度
    */
    /* 用于 CSS 过渡效果的持续时间，
    表示元素从一个状态到另一个状态的动画时间 */
    --transition-duration: 0.3s;
    /* 用于 CSS 过渡效果的延迟时间，
    表示动画开始前的等待时间 */
    --transition-delay: 0s;
    /* 用于 CSS 动画效果的速度，
    表示动画完成一次循环所需的时间 */
    --animation-speed: 1s;
}