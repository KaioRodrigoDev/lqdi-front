<template>
  <div>
    <Banner />
    <Content />
    <Form />
  </div>
</template>

<script>
import Banner from '@/components/home/banner'
import Content from '@/components/home/content'
import Form from '@/components/home/formSection'

export default {
  components: {
    Banner,
    Content,
    Form
  }
}
</script>
