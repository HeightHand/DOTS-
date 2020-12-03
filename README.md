# DOTS-

1.用了 [BurstCompile] 的函数里如果有 static 属性，发布时会出错，发布失败。

2.添加 PhysicsVelocity 时，PhysicsMass要设置 Transform数值(例如：rot = Quaternion.identity)，如果使用默认数值物体的位置信息变成 NAN.
