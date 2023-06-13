<Canvas>

    <PerspectiveCamera
        position={{ x:20, y:20, z:20 }}
    >
        <OrbitControls/>
    </PerspectiveCamera>

    <GLTF url="models/duckkie2.2.glb"/>

    <AmbientLight color="white" intensity={0.2} />

    <DirectionalLight
        color="white"
        intensity={2}
        position={{ x:10, y:20 }}
    />

</Canvas>

<script lang="ts">
    import { Canvas, PerspectiveCamera, OrbitControls, Mesh, AmbientLight, DirectionalLight} from '@threlte/core'
    import * as Three from 'three'
    import { GLTF } from '@threlte/extras'
    import * as Utils from 'three/src/math/MathUtils.js'



</script>