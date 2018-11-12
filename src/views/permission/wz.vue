<template>
  <div class="animated fadeIn">

    <el-row>
      <el-col :sm="24" :md="24" :lg="12">
        <h3>wwwwwwwwwww</h3>
        <p>edsdasdfasdfasdf</p>
      </el-col>
    </el-row>
    <el-table :columns="columns1" :data="data1"/>
  </div>
</template>

<script>
export default {
  data() {
    return {
      columns1: [
        {
          title: 'er',
          key: 'name'
        },
        {
          title: 'qw',
          key: 'age'
        },
        {
          title: 'dd',
          key: 'address'
        }
      ],
      data1: [
        { name: 'ss', age: 10, address: 'yhrty' },
        { name: 'dd2', age: 12, address: 'fgh' },
        { name: 'ff3', age: 14, address: 'asdf' }
      ]
    }
  }
}
</script>
