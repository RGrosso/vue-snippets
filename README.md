# RG Vue Snippets

This extension is a Vue 3 Snippets extension for Visual Studio Code.

## Snippets

There are three sets of snippets available for Vue, Vue JavaScript and Vue Template.

### Vue Templates

| Prefix      | Snippet Content                          |
| ----------- | ---------------------------------------- |
| vss         | Vue Script Setup                         |
| vs          | Vue Setup                                |
| vsn         | Vue Setup named                          |
| ts-vss      | TypeScript Vue Script Setup              |
| ts-vs       | TypeScript Vue Setup                     |
| ts-vsn      | TypeScript Vue Setup named               |
| style       | Style tag SCSS and scoped                |
| stylelang   | Style tag custom lang and scoped         |
| script      | Script element with export default       |
| scriptsetup | Script setup element                     |
| scriptname  | Script element with export default named |
| template    | Vue template element                     |

### Vue JavaScript

| Prefix            | Snippet Content                                               |
| ----------------- | ------------------------------------------------------------- |
| ifv               | `Import from Vue`                                             |
| reactive          | `const obj = reactive({});`                                   |
| ref               | `const foo = ref({});`                                        |
| computed          | `const foo = computed(() => {});`                             |
| watch             | `watch(foo, () => {});`                                       |
| watchfull         | `watch(foo, (newValue, prevValue) => {});`                    |
| setup             | `setup() { }`                                                 |
| vdimport          | `import ComponentName from "@/components/ComponentName.vue";` |
| vimport           | `import ComponentName from "./components/ComponentName.vue";` |
| onBeforeMount     | `onBeforeMount(() => {});`                                    |
| onMounted         | `onMounted(() => {});`                                        |
| onBeforeUpdate    | `onBeforeUpdate(() => {});`                                   |
| onUpdated         | `onUpdated(() => {});`                                        |
| onBeforeUnmount   | `onBeforeUnmount(() => {});`                                  |
| onUnmounted       | `onUnmounted(() => {});`                                      |
| onErrorCaptured   | `onErrorCaptured(() => {});`                                  |
| onRenderTracked   | `onRenderTracked(() => {});`                                  |
| onRenderTriggered | `onRenderTriggered(() => {});`                                |
| defineProps       | `const props = defineProps({}); `                             |
| defineEmits       | `const props = defineEmits({}); `                             |

### Vue Template

| Prefix       | Snippet Content                               |
| ------------ | --------------------------------------------- |
| v-for        | `v-for="(item) in items" :key="index"`        |
| v-for-i      | `v-for="(item, index) in items" :key="index"` |
| v-if         | `v-if="condition"`                            |
| v-if-el      | `v-else-if="condition"`                       |
| v-el         | `v-else`                                      |
| component    | `<component :is="componentId" />`             |
| routerlink   | `<router-link> </router-link>`                |
| routerlinkto | `<router-link to=" "> </router-link>`         |
