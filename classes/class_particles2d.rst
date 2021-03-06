.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Particles2D.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Particles2D:

Particles2D
===========

**Inherits:** :ref:`Node2D<class_node2d>` **<** :ref:`CanvasItem<class_canvasitem>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

2D particle emitter.

Member Functions
----------------

+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`Rect2<class_rect2>`        | :ref:`capture_rect<class_Particles2D_capture_rect>` **(** **)** const                                                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`            | :ref:`get_amount<class_Particles2D_get_amount>` **(** **)** const                                                        |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`            | :ref:`get_draw_order<class_Particles2D_get_draw_order>` **(** **)** const                                                |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`        | :ref:`get_explosiveness_ratio<class_Particles2D_get_explosiveness_ratio>` **(** **)** const                              |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`            | :ref:`get_fixed_fps<class_Particles2D_get_fixed_fps>` **(** **)** const                                                  |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`          | :ref:`get_fractional_delta<class_Particles2D_get_fractional_delta>` **(** **)** const                                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`            | :ref:`get_h_frames<class_Particles2D_get_h_frames>` **(** **)** const                                                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`        | :ref:`get_lifetime<class_Particles2D_get_lifetime>` **(** **)** const                                                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`Texture<class_texture>`    | :ref:`get_normal_map<class_Particles2D_get_normal_map>` **(** **)** const                                                |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`          | :ref:`get_one_shot<class_Particles2D_get_one_shot>` **(** **)** const                                                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`        | :ref:`get_pre_process_time<class_Particles2D_get_pre_process_time>` **(** **)** const                                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`Material<class_material>`  | :ref:`get_process_material<class_Particles2D_get_process_material>` **(** **)** const                                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`        | :ref:`get_randomness_ratio<class_Particles2D_get_randomness_ratio>` **(** **)** const                                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`        | :ref:`get_speed_scale<class_Particles2D_get_speed_scale>` **(** **)** const                                              |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`Texture<class_texture>`    | :ref:`get_texture<class_Particles2D_get_texture>` **(** **)** const                                                      |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`          | :ref:`get_use_local_coordinates<class_Particles2D_get_use_local_coordinates>` **(** **)** const                          |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`            | :ref:`get_v_frames<class_Particles2D_get_v_frames>` **(** **)** const                                                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`Rect2<class_rect2>`        | :ref:`get_visibility_rect<class_Particles2D_get_visibility_rect>` **(** **)** const                                      |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`          | :ref:`is_emitting<class_Particles2D_is_emitting>` **(** **)** const                                                      |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`restart<class_Particles2D_restart>` **(** **)**                                                                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_amount<class_Particles2D_set_amount>` **(** :ref:`int<class_int>` amount **)**                                 |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_draw_order<class_Particles2D_set_draw_order>` **(** :ref:`int<class_int>` order **)**                          |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_emitting<class_Particles2D_set_emitting>` **(** :ref:`bool<class_bool>` emitting **)**                         |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_explosiveness_ratio<class_Particles2D_set_explosiveness_ratio>` **(** :ref:`float<class_float>` ratio **)**    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_fixed_fps<class_Particles2D_set_fixed_fps>` **(** :ref:`int<class_int>` fps **)**                              |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_fractional_delta<class_Particles2D_set_fractional_delta>` **(** :ref:`bool<class_bool>` enable **)**           |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_h_frames<class_Particles2D_set_h_frames>` **(** :ref:`int<class_int>` frames **)**                             |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_lifetime<class_Particles2D_set_lifetime>` **(** :ref:`float<class_float>` secs **)**                           |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_normal_map<class_Particles2D_set_normal_map>` **(** :ref:`Texture<class_texture>` texture **)**                |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_one_shot<class_Particles2D_set_one_shot>` **(** :ref:`bool<class_bool>` secs **)**                             |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_pre_process_time<class_Particles2D_set_pre_process_time>` **(** :ref:`float<class_float>` secs **)**           |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_process_material<class_Particles2D_set_process_material>` **(** :ref:`Material<class_material>` material **)** |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_randomness_ratio<class_Particles2D_set_randomness_ratio>` **(** :ref:`float<class_float>` ratio **)**          |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_speed_scale<class_Particles2D_set_speed_scale>` **(** :ref:`float<class_float>` scale **)**                    |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_texture<class_Particles2D_set_texture>` **(** :ref:`Texture<class_texture>` texture **)**                      |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_use_local_coordinates<class_Particles2D_set_use_local_coordinates>` **(** :ref:`bool<class_bool>` enable **)** |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_v_frames<class_Particles2D_set_v_frames>` **(** :ref:`int<class_int>` frames **)**                             |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+
| void                             | :ref:`set_visibility_rect<class_Particles2D_set_visibility_rect>` **(** :ref:`Rect2<class_rect2>` aabb **)**             |
+----------------------------------+--------------------------------------------------------------------------------------------------------------------------+

Member Variables
----------------

  .. _class_Particles2D_amount:

- :ref:`int<class_int>` **amount** - Number of particles emitted in one emission cycle.

  .. _class_Particles2D_draw_order:

- :ref:`int<class_int>` **draw_order** - Particle draw order. Uses ``DRAW_ORDER\_\*`` values. Default value: ``DRAW_ORDER_INDEX``.

  .. _class_Particles2D_emitting:

- :ref:`bool<class_bool>` **emitting** - If ``true`` particles are being emitted. Default value: ``true``.

  .. _class_Particles2D_explosiveness:

- :ref:`float<class_float>` **explosiveness** - How rapidly particles in an emission cycle are emitted. If greater than ``0``, there will be a gap in emissions before the next cycle begins. Default value: ``0``.

  .. _class_Particles2D_fixed_fps:

- :ref:`int<class_int>` **fixed_fps**

  .. _class_Particles2D_fract_delta:

- :ref:`bool<class_bool>` **fract_delta**

  .. _class_Particles2D_h_frames:

- :ref:`int<class_int>` **h_frames** - Number of horizontal frames in ``texture``.

  .. _class_Particles2D_lifetime:

- :ref:`float<class_float>` **lifetime** - Amount of time each particle will exist. Default value: ``1``.

  .. _class_Particles2D_local_coords:

- :ref:`bool<class_bool>` **local_coords** - If ``true`` particles use the parent node's coordinate space. If ``false`` they use global coordinates. Default value: ``true``.

  .. _class_Particles2D_normal_map:

- :ref:`Texture<class_texture>` **normal_map**

  .. _class_Particles2D_one_shot:

- :ref:`bool<class_bool>` **one_shot** - If ``true`` only one emission cycle occurs. If set ``true`` during a cycle, emission will stop at the cycle's end. Default value: ``false``.

  .. _class_Particles2D_preprocess:

- :ref:`float<class_float>` **preprocess** - Particle system starts as if it had already run for this many seconds.

  .. _class_Particles2D_process_material:

- :ref:`Material<class_material>` **process_material** - :ref:`Material<class_material>` for processing particles. Can be a :ref:`ParticlesMaterial<class_particlesmaterial>` or a :ref:`ShaderMaterial<class_shadermaterial>`.

  .. _class_Particles2D_randomness:

- :ref:`float<class_float>` **randomness** - Emission lifetime randomness ratio. Default value: ``0``.

  .. _class_Particles2D_speed_scale:

- :ref:`float<class_float>` **speed_scale** - Particle system's running speed scaling ratio. Default value: ``1``.

  .. _class_Particles2D_texture:

- :ref:`Texture<class_texture>` **texture** - Particle texture. If ``null`` particles will be squares.

  .. _class_Particles2D_v_frames:

- :ref:`int<class_int>` **v_frames** - Number of vertical frames in ``texture``.

  .. _class_Particles2D_visibility_rect:

- :ref:`Rect2<class_rect2>` **visibility_rect** - Editor visibility helper.


Numeric Constants
-----------------

- **DRAW_ORDER_INDEX** = **0** --- Particles are drawn in the order emitted.
- **DRAW_ORDER_LIFETIME** = **1** --- Particles are drawn in order of remaining lifetime.

Description
-----------

2D particle node used to create a variety of particle systems and effects. ``Particles2D`` features an emitter that generates some number of particles at a given rate.

Use the ``process_material`` property to add a :ref:`ParticlesMaterial<class_particlesmaterial>` to configure particle appearance and behavior. Alternatively, you can add a :ref:`ShaderMaterial<class_shadermaterial>` which will be applied to all particles.

Member Function Description
---------------------------

.. _class_Particles2D_capture_rect:

- :ref:`Rect2<class_rect2>` **capture_rect** **(** **)** const

.. _class_Particles2D_get_amount:

- :ref:`int<class_int>` **get_amount** **(** **)** const

Returns the amount of particles spawned at each emission

.. _class_Particles2D_get_draw_order:

- :ref:`int<class_int>` **get_draw_order** **(** **)** const

.. _class_Particles2D_get_explosiveness_ratio:

- :ref:`float<class_float>` **get_explosiveness_ratio** **(** **)** const

.. _class_Particles2D_get_fixed_fps:

- :ref:`int<class_int>` **get_fixed_fps** **(** **)** const

.. _class_Particles2D_get_fractional_delta:

- :ref:`bool<class_bool>` **get_fractional_delta** **(** **)** const

.. _class_Particles2D_get_h_frames:

- :ref:`int<class_int>` **get_h_frames** **(** **)** const

.. _class_Particles2D_get_lifetime:

- :ref:`float<class_float>` **get_lifetime** **(** **)** const

Gets the amount of seconds that each particle will be visible.

.. _class_Particles2D_get_normal_map:

- :ref:`Texture<class_texture>` **get_normal_map** **(** **)** const

.. _class_Particles2D_get_one_shot:

- :ref:`bool<class_bool>` **get_one_shot** **(** **)** const

.. _class_Particles2D_get_pre_process_time:

- :ref:`float<class_float>` **get_pre_process_time** **(** **)** const

.. _class_Particles2D_get_process_material:

- :ref:`Material<class_material>` **get_process_material** **(** **)** const

.. _class_Particles2D_get_randomness_ratio:

- :ref:`float<class_float>` **get_randomness_ratio** **(** **)** const

.. _class_Particles2D_get_speed_scale:

- :ref:`float<class_float>` **get_speed_scale** **(** **)** const

.. _class_Particles2D_get_texture:

- :ref:`Texture<class_texture>` **get_texture** **(** **)** const

Returns the texture for emitted particles

.. _class_Particles2D_get_use_local_coordinates:

- :ref:`bool<class_bool>` **get_use_local_coordinates** **(** **)** const

.. _class_Particles2D_get_v_frames:

- :ref:`int<class_int>` **get_v_frames** **(** **)** const

.. _class_Particles2D_get_visibility_rect:

- :ref:`Rect2<class_rect2>` **get_visibility_rect** **(** **)** const

.. _class_Particles2D_is_emitting:

- :ref:`bool<class_bool>` **is_emitting** **(** **)** const

Returns whether this emitter is currently emitting or not

.. _class_Particles2D_restart:

- void **restart** **(** **)**

.. _class_Particles2D_set_amount:

- void **set_amount** **(** :ref:`int<class_int>` amount **)**

Sets the amount of particles spawned at each emission

.. _class_Particles2D_set_draw_order:

- void **set_draw_order** **(** :ref:`int<class_int>` order **)**

.. _class_Particles2D_set_emitting:

- void **set_emitting** **(** :ref:`bool<class_bool>` emitting **)**

If this is set to true then the particle emitter will emit particles, if its false it will not.

.. _class_Particles2D_set_explosiveness_ratio:

- void **set_explosiveness_ratio** **(** :ref:`float<class_float>` ratio **)**

.. _class_Particles2D_set_fixed_fps:

- void **set_fixed_fps** **(** :ref:`int<class_int>` fps **)**

.. _class_Particles2D_set_fractional_delta:

- void **set_fractional_delta** **(** :ref:`bool<class_bool>` enable **)**

.. _class_Particles2D_set_h_frames:

- void **set_h_frames** **(** :ref:`int<class_int>` frames **)**

.. _class_Particles2D_set_lifetime:

- void **set_lifetime** **(** :ref:`float<class_float>` secs **)**

Sets the amount of seconds that each particle will be visible.

.. _class_Particles2D_set_normal_map:

- void **set_normal_map** **(** :ref:`Texture<class_texture>` texture **)**

.. _class_Particles2D_set_one_shot:

- void **set_one_shot** **(** :ref:`bool<class_bool>` secs **)**

.. _class_Particles2D_set_pre_process_time:

- void **set_pre_process_time** **(** :ref:`float<class_float>` secs **)**

.. _class_Particles2D_set_process_material:

- void **set_process_material** **(** :ref:`Material<class_material>` material **)**

.. _class_Particles2D_set_randomness_ratio:

- void **set_randomness_ratio** **(** :ref:`float<class_float>` ratio **)**

.. _class_Particles2D_set_speed_scale:

- void **set_speed_scale** **(** :ref:`float<class_float>` scale **)**

.. _class_Particles2D_set_texture:

- void **set_texture** **(** :ref:`Texture<class_texture>` texture **)**

.. _class_Particles2D_set_use_local_coordinates:

- void **set_use_local_coordinates** **(** :ref:`bool<class_bool>` enable **)**

.. _class_Particles2D_set_v_frames:

- void **set_v_frames** **(** :ref:`int<class_int>` frames **)**

.. _class_Particles2D_set_visibility_rect:

- void **set_visibility_rect** **(** :ref:`Rect2<class_rect2>` aabb **)**


