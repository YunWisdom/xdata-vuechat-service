<template>
    <div class="privacy">
        <header id="wx-header">
            <!--<div class="other"><span>添加朋友</span></div>-->
            <div class="center">
                <router-link to="/self/settings" tag="div" class="iconfont icon-left">
                    <span>设置</span>
                </router-link>
                <span>隐私</span>
            </div>
        </header>
        <section>
            <div class="weui-cells__title">联系人</div>
            <div class="weui-cells">
                <div class="weui-cell weui-cell_switch">
                    <div class="weui-cell__bd">加我为朋友时需要验证</div>
                    <div class="weui-cell__ft"><input type="checkbox" class="weui-switch"></div>
                </div>
            </div>
            <div class="weui-cells">
                <div class="weui-cell weui-cell_switch">
                    <div class="weui-cell__bd">通过账号搜索到我</div>
                    <div class="weui-cell__ft"><input type="checkbox" class="weui-switch" checked=""></div>
                </div>
            </div>
            <div class="weui-cells">
                <div class="weui-cell weui-cell_switch">
                    <div class="weui-cell__bd">通过账号搜索到我</div>
                    <div class="weui-cell__ft"><input type="checkbox" class="weui-switch" checked=""></div>
                </div>
            </div>
            <div class="weui-cells__tips">关闭后, 其他用户将不能通过账号搜索到你</div>
            <div class="weui-cells">
                <div class="weui-cell">
                    <div class="weui-cell__bd">联系人黑名单</div>
                    <div class="weui-cell__ft"></div>
                </div>
            </div>
            <div class="weui-cells__title">圈子</div>
            <div class="weui-cells">
                <div class="weui-cell">
                    <div class="weui-cell__bd">不让他(她)看我的圈子</div>
                    <div class="weui-cell__ft"></div>
                </div>
                <div class="weui-cell">
                    <div class="weui-cell__bd">不看他(她)看的圈子</div>
                    <div class="weui-cell__ft"></div>
                </div>
            </div>
            <div class="weui-cells">
                <div class="weui-cell weui-cell_switch">
                    <div class="weui-cell__bd">允许陌生人查看十张照片</div>
                    <div class="weui-cell__ft"><input type="checkbox" class="weui-switch" checked=""></div>
                </div>
            </div>
        </section>
    </div>
</template>
<script>
    export default {}

</script>
