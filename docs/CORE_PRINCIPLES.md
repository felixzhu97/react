# React框架核心原理

## 1. 虚拟DOM与协调算法
- **虚拟DOM**：轻量级的JavaScript对象表示
- **协调过程**：通过Diff算法比较新旧虚拟DOM
- **Fiber架构**：可中断的渐进式渲染

## 2. 组件生命周期
- **挂载阶段**：constructor → render → componentDidMount
- **更新阶段**：shouldComponentUpdate → render → componentDidUpdate  
- **卸载阶段**：componentWillUnmount

## 3. Hooks系统
- **状态管理**：useState, useReducer
- **副作用处理**：useEffect, useLayoutEffect
- **性能优化**：useMemo, useCallback

## 4. 事件系统
- 合成事件(SyntheticEvent)
- 事件委托机制
- 跨浏览器兼容处理

## 5. 并发模式
- 时间切片(Time Slicing)
- 优先级调度
- Suspense异步渲染
