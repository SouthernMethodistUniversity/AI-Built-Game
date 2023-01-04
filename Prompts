Scripting Prompts

Scripting Prompt 1:
write a player movement script for unity 2d using rigidbody
OpenGPT Output 1:
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class PlayerMovement : MonoBehaviour
{
    public float speed = 10.0f;
    private Rigidbody2D rb;

    void Start()
    {
        rb = GetComponent<Rigidbody2D>();
    }

    void Update()
    {
        float horizontalInput = Input.GetAxis("Horizontal");
        float verticalInput = Input.GetAxis("Vertical");

        Vector2 movement = new Vector2(horizontalInput, verticalInput);

        rb.AddForce(movement * speed);
    }
}

Scripting Prompt 2:
write unity script to reload level on key press r

OpenGPT Output 2:
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.SceneManagement;

public class ReloadLevel : MonoBehaviour
{
    void Update()
    {
        if (Input.GetKeyDown(KeyCode.R))
        {
            SceneManager.LoadScene(SceneManager.GetActiveScene().name);
        }
    }
}

Art Prompts

Stable Diffusion Prompt 1:
2d video game character sprite
Stable Diffusion Output 1:
 

Stable Diffusion Prompt 2: 
2d video game grass platform
Stable Diffusion Output 2:
 
