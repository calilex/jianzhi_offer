至于当三个数字一样时，没法确定中间的属于哪个部分，可以举例说明。
每次也必须先从左边分之开始比较left=mid+1, 举例`------------___` 只有从左才能得到正确答案，从右right=mid就找不到答案了。
