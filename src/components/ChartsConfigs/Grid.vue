<template>
  <el-form label-position="top">
    <el-row :gutter="10">
      <el-col :span="24">
        <el-form-item label="Show（是否显示）">
          <el-input class="eo-input"></el-input>
        </el-form-item>
      </el-col>
      <el-col :span="24">
        <el-form-item label="Id">
          <el-input class="eo-input"></el-input>
        </el-form-item>
      </el-col>
    </el-row>
    <eo-padding></eo-padding>
    <el-row :gutter="10">
      <el-col :span="12">
        <el-form-item label="Width">
          <el-input class="eo-input"></el-input>
        </el-form-item>
      </el-col>
      <el-col :span="12">
        <el-form-item label="Height">
          <el-input class="eo-input"></el-input>
        </el-form-item>
      </el-col>
      <el-col :span="12">
        <el-form-item label="ContainLabel:">
          <el-input class="eo-input"></el-input>
        </el-form-item>
      </el-col>
      <el-col :span="24">
        <el-form-item label="BackgroundColor:">
          <el-input class="eo-input"></el-input>
        </el-form-item>
      </el-col>
      <el-col :span="24">
        <el-form-item label="BorderColor:">
          <el-input class="eo-input"></el-input>
        </el-form-item>
      </el-col>
    </el-row>
  </el-form>
</template>

<script>
  import EoPadding from './Padding';

  export default {
    name: 'EoChartGrid',
    components: {
      EoPadding
    }
  };
</script>
