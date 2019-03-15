# append 的坑

## Slice 扩容的坑

来自：https://leetcode-cn.com/problems/subsets

错误代码：

```golang
func subsets(nums []int) (ret [][]int) {
	ret = [][]int{make([]int, 0)}
	for i := 0; i < len(nums); i++ {
		l := len(ret)
		for j := 0; j < l; j++ {
			ret = append(ret, append(ret[j], nums[i]))
		}
	}
	return
}
```

原理参考：https://studygolang.com/articles/10924
