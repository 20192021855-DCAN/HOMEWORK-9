##  p2

> x to z:
>
> x-y-z,x-y-w-z,
>
> x-w-z,x-w-y-z,
>
> x-v-w-z,x-v-w-y-z,
>
> x-u-w-z,x-u-v-w-u-z
>
> x-u-v-w-z,x-u-v-w-y-z
>
> z to u:
>
> z-w-u,
>
> z-w-v-u,z-w-x-u,z-w-v-x-u,z-w-x-v-u,z-w-y-x-u,z-w-y-x-v-u,
>
> z-y-x-u,z-y-x-v-u,z-y-x-w-u,z-y-x-w-y-u,z-y-x-v-w-u,
>
> z-y-w-v-u,z-y-w-x-u,z-y-w-v-x-u,z-y-w-x-v-u,z-y-w-y-x-u,z-y-w-y-x-v-u
>
> z to w:
>
> z-w,z-y-w,z-y-x-w,z-y-x-v-w,z-y-x-u-w,z-y-x-u-v-w,z-y-x-v-u-w

 ## p9

>  不，这是因为降低链路成本不会导致循环(由该链路的两个节点之间的下一跳关系引起)。将两个节点连接到一个链路相当于将链路重量从无限降到有限权。 

## p10

>  在每一步中，节点距离向量的每一次更新都是基于Bellman-Ford方程，即只减少距离向量中的这些值。价值没有增加。如果没有更新，则不会发送消息。因此，D(X)是不增加的。由于这些代价是有限的，那么最终距离向量将稳定在有限的步骤。 