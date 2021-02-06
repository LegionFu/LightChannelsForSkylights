# LightChannelsForSkylights
UE4.25 Support light channels for sky lights

1. 替换UE_4.25\Engine\Shaders\Private目录下的ReflectionEnvironmentPixelShader.usf

2. 场景内的skylight的mobility选择Movable

3. 场景内需要不受skylight影响的mesh勾选Lighting channels下的Channel 2即可

注：
在官方提供的示例场景：照片级渲染(Realistic Rendering)下测试通过。
