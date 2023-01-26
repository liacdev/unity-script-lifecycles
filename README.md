# unity-script-lifecycle-overview
This repo is a place for notes about Unity's Script Lifecycle

# Main branch: Table of contents
Branch 1: Initialization 
- Awake
- OnEnable 

Branch 2: Editor
- Reset

Branch 3: Initialization
- Start

Branch 4: Physics
- FixedUpdate
- Internal animation update
- State machine update
- OnStateMachineEnter/Exit
- ProcessGraph
- Fire animatin events
- StateMachineBevaviour callbacks
- OnAnimatorMove
- Internal physics update
- Process animation
- OnAnimator1K
- WriteTransform
- WriteProperties
- OnTriggerXXX
- OnCollisionXXX
- yield WaitForFixedUpdate

Branch 5: Input events
- OnMouseXXX

Branch 6: Game logic
- Update
- yield null
- yield WaitForSeconds
- yield WWW
- yield StartCoroutine
- StateMachineUpdate
- OnStateMachineEnter/Exit
- ProcessGraph
- Fire animation events
- StateMachineBehavious callbacks
- OnAnimatorMove
- ProcessAnimation
- OnAnimator1K
- WriteTransform
- WriteProperties
- LateUpdate

Branch 7: Scene rendering
- OnPreCull
- OnWillRenderObject
- OnBecameVisible
- OnBecameInvisible
- OnPreRender
- OnRenderObject
- OnPostRender
- OnRenderImage

Branch 8: Gizmo rendering
- OnDrawGizmos

Branch 9: GUI rendering
- OnGUI

Branch 10: End of frame
- yield WaitForEndOfFrame

Branch 11: Pausing
- OnApplicationPause

Branch 12: Decommissioning
- OnApplicationQuit
- OnDisable
- OnDestroy

