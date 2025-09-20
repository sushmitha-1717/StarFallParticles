using UnityEngine;

public class StarController : MonoBehaviour
{
    private ParticleSystem ps;

    void Start()
    {
        ps = GetComponent<ParticleSystem>(); // must be attached to the particle system
    }

    void Update()
    {
        // Toggle particle emission
        if (Input.GetKeyDown(KeyCode.Space))
        {
            var emission = ps.emission;
            emission.enabled = !emission.enabled;
        }

        // Change particle color randomly
        if (Input.GetKeyDown(KeyCode.C))
        {
            var main = ps.main;
            main.startColor = new ParticleSystem.MinMaxGradient(Random.ColorHSV());
        }
    }
}
