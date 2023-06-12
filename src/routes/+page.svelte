<Threlte.Canvas>

    <Threlte.PerspectiveCamera
        position={{ x:20, y:20, z:20 }}
    >
        <Threlte.OrbitControls/>
    </Threlte.PerspectiveCamera>
    
    <Threlte.Mesh
        geometry={new Three.SphereGeometry(4,64,64)}
        material={new Three.MeshStandardMaterial({ color: 'white' })}
    />

    <Threlte.AmbientLight color="white" intensity={0.2} />

    <Threlte.DirectionalLight
        color="white"
        intensity={2}
        position={{ x:10, y:20 }}
    />

</Threlte.Canvas>

<script lang="ts">
    import * as Threlte from '@threlte/core'
    import * as Three from 'three'
    import * as Utils from 'three/src/math/MathUtils.js'
</script>