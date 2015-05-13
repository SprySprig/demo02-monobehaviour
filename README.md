# demo02-monobehaviour

Exploring the MonoBehaviour

```
using UnityEngine;

public class MyClass : MonoBehaviour
{
    /** PREFAB VARIABLES **/
    public string Name;

    /** PRIVATE **/
    private float Size = 0.0f;

    /** PUBLIC **/
    public bool IsAwesome { get; set; }

    // Use this for initialization
    internal void Start()
    {
    }

    // Update is called once per frame
    internal void Update()
    {
    }

    // Get for free with BoxCollider2D?
    internal void OnMouseUp()
    {
    }
}
```
