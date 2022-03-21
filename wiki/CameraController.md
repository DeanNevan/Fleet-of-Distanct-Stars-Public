**Inherits:** _[Camera](https://docs.godotengine.org/en/stable/classes/class_camera.html) > [Spatial](https://docs.godotengine.org/en/stable/classes/class_spatial.html) > [Node](https://docs.godotengine.org/en/stable/classes/class_node.html) > [Object](https://docs.godotengine.org/en/stable/classes/class_object.html)_  
## Description  
  
## Properties 
  
| type | property | default value |  
| ---- | -------- | ------------- |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | [movement_speed](cameracontroller#movement_speed) | `30` |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | [movement_damping](cameracontroller#movement_damping) | `0.74` |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | [edge_size](cameracontroller#edge_size) | `0` |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | [min_zoom](cameracontroller#min_zoom) | `3` |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | [max_zoom](cameracontroller#max_zoom) | `25` |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | [zoom_sensibility](cameracontroller#zoom_sensibility) | `0.1` |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | [rotation_sensibility](cameracontroller#rotation_sensibility) | `10` |  
| [NodePath](https://docs.godotengine.org/en/stable/classes/class_nodepath.html) | [origin_node_path](cameracontroller#origin_node_path) | `""` |  
| [Spatial](https://docs.godotengine.org/en/stable/classes/class_spatial.html) | [origin](cameracontroller#origin) | `Null` |  
| [float](https://docs.godotengine.org/en/stable/classes/class_float.html) | [init_pitch](cameracontroller#init_pitch) | `Null` |  
| [float](https://docs.godotengine.org/en/stable/classes/class_float.html) | [init_yaw](cameracontroller#init_yaw) | `Null` |  
| [float](https://docs.godotengine.org/en/stable/classes/class_float.html) | [pitch](cameracontroller#pitch) | `Null` |  
| [float](https://docs.godotengine.org/en/stable/classes/class_float.html) | [yaw](cameracontroller#yaw) | `Null` |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | [current_action](cameracontroller#current_action) | `Null` |  
| [Vector2](https://docs.godotengine.org/en/stable/classes/class_vector2.html) | [velocity](cameracontroller#velocity) | `Null` |  
  
## Methods 
  
| return type | method signature |  
| ----------- | ---------------- |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | **[change_action](cameracontroller#change_action)**([Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) action) |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | **[change_velocity](cameracontroller#change_velocity)**([Vector2](https://docs.godotengine.org/en/stable/classes/class_vector2.html) _velocity) |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | **[move](cameracontroller#move)**([Vector2](https://docs.godotengine.org/en/stable/classes/class_vector2.html) _velocity) |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | **[zoom](cameracontroller#zoom)**([float](https://docs.godotengine.org/en/stable/classes/class_float.html) direction) |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | **[rotate_view](cameracontroller#rotate_view)**([Vector2](https://docs.godotengine.org/en/stable/classes/class_vector2.html) axis) |  
| [Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) | **[reset_rotation](cameracontroller#reset_rotation)**() |  
  
## Enumerations  
  
  
enum **CAMERA_ACTIONS**: 
  
- **MOVING = 0**  
- **ROTATING_VIEW = 1**  
---------
  
## Properties Descriptions  
  
### movement_speed 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **movement_speed**  
  
<table><tbody>  
<tr> <th>_Default_</th> <th>`30`</th> </tr>  
</tbody></table>  
---------
### movement_damping 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **movement_damping**  
  
<table><tbody>  
<tr> <th>_Default_</th> <th>`0.74`</th> </tr>  
</tbody></table>  
---------
### edge_size 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **edge_size**  
  
<table><tbody>  
<tr> <th>_Default_</th> <th>`0`</th> </tr>  
</tbody></table>Value in percentage of screen portion
A value of 0.3 means that when you place the cursor 30% or less away from an edge it will start pushing the camera
  
---------
### min_zoom 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **min_zoom**  
  
<table><tbody>  
<tr> <th>_Default_</th> <th>`3`</th> </tr>  
</tbody></table>EDIT HERE--->**,***<--- ZOOM MIN AND MAX LIMITS
  
---------
### max_zoom 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **max_zoom**  
  
<table><tbody>  
<tr> <th>_Default_</th> <th>`25`</th> </tr>  
</tbody></table>EDIT HERE--->**,***<--- ZOOM MIN AND MAX LIMITS
  
---------
### zoom_sensibility 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **zoom_sensibility**  
  
<table><tbody>  
<tr> <th>_Default_</th> <th>`0.1`</th> </tr>  
</tbody></table>  
---------
### rotation_sensibility 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **rotation_sensibility**  
  
<table><tbody>  
<tr> <th>_Default_</th> <th>`10`</th> </tr>  
</tbody></table>  
---------
### origin_node_path 
- _[NodePath](https://docs.godotengine.org/en/stable/classes/class_nodepath.html)_ **origin_node_path**  
  
<table><tbody>  
<tr> <th>_Default_</th> <th>``</th> </tr>  
</tbody></table>  
---------
### origin 
- _[Spatial](https://docs.godotengine.org/en/stable/classes/class_spatial.html)_ **origin**  
  
  
---------
### init_pitch 
- _[float](https://docs.godotengine.org/en/stable/classes/class_float.html)_ **init_pitch**  
  
  
---------
### init_yaw 
- _[float](https://docs.godotengine.org/en/stable/classes/class_float.html)_ **init_yaw**  
  
  
---------
### pitch 
- _[float](https://docs.godotengine.org/en/stable/classes/class_float.html)_ **pitch**  
  
  
---------
### yaw 
- _[float](https://docs.godotengine.org/en/stable/classes/class_float.html)_ **yaw**  
  
  
---------
### current_action 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **current_action**  
  
  
---------
### velocity 
- _[Vector2](https://docs.godotengine.org/en/stable/classes/class_vector2.html)_ **velocity**  
  
  
---------
## Method Descriptions  
  
### change_action 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **change_action**([Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html) action) 
  
  
---------
### change_velocity 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **change_velocity**([Vector2](https://docs.godotengine.org/en/stable/classes/class_vector2.html) _velocity) 
  
	match(current_action):
		CAMERA_ACTIONS.MOVING:
			#CAMERA MOVEMENT
			velocity.x = clamp(velocity.x * movement_damping,-1.0,1.0)
			velocity.y = clamp(velocity.y * movement_damping,-1.0,1.0)

			if velocity != Vector2.ZERO:
				move(velocity)
  
---------
### move 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **move**([Vector2](https://docs.godotengine.org/en/stable/classes/class_vector2.html) _velocity) 
  
  
---------
### zoom 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **zoom**([float](https://docs.godotengine.org/en/stable/classes/class_float.html) direction) 
  
  
---------
### rotate_view 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **rotate_view**([Vector2](https://docs.godotengine.org/en/stable/classes/class_vector2.html) axis) 
  
  
---------
### reset_rotation 
- _[Variant](https://docs.godotengine.org/en/stable/classes/class_variant.html)_ **reset_rotation**() 
  
  
---------
