<template>
  <div class="wrapper">
    <ul>
        <li @click="interestCircle">
            <img src="../assets/image/li1.png" alt="">
            <span>兴趣圈</span>
        </li>
        <li @click="topicCenter">
            <img src="../assets/image/li2.png" alt="">
            <span>话题中心</span>
        <li @click="activityCenter">
            <img src="../assets/image/li3.png" alt="">
            <span>活动中心</span>
        </li>
    </ul>
    <ul>
        <li @click="originalList">
            <img src="../assets/image/li4.png" alt="">
            <span>原创排行榜</span>
        </li>
        <li @click="allList">
            <img src="../assets/image/li5.png" alt="">
            <span>全区排行榜</span>
        </li>

    </ul>
    <ul>
        <li @click="gameCenter">
            <img src="../assets/image/li6.png" alt="">
            <span>游戏中心</span>
        </li>
        <li @click="aroundShop">
            <img src="../assets/image/li7.png" alt="">
            <span>周边商城</span>
        </li>

    </ul>
  </div>
</template>

<script>
export default {
    data () {
        return {
            
        }
    },
    computed: {

    },
    methods: {
        interestCircle () {
            console.log('this is a circle of interest')
        },
        topicCenter () {
            console.log('this is a center of topic')
         },
        activityCenter () {
            console.log('this is a circle of activity')
        },
        originalList () {
            console.log('this is a original list')
        },
        allList () {
            console.log('this is a all list')
        },
        gameCenter () {
            console.log('this is a circle of game')
        },
        aroundShop () {
            console.log('this is a shopping')
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../assets/css/find.scss';
</style>