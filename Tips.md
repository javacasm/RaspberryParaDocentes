# Tips

* Si aparece el rayito en pantalla, vamos flojos de alimentación. Con la nueva Raspi 3 necesitamos 2.5A-3A
![Rayito](https://s9.postimg.org/b062013wb/under_volt.png)
* Tener varias tarjetas para varios sistemas
* Usar el gestor de tareas para ver si algún proceso se ha colgado
* Incluir indicadores en el panel superior para ver temperatura/cpu
* Problema de sonido en Ubuntu Mate
	Modificar /boot/config.txt con

      sudo nano /boot/config.txt

  Añadimos las siguientes líneas

      hdmi_drive=2
      hdmi_force_hotplug=1
      config_hdmi_boost=4


      Ctrl+O para guardar

      Ctrl+x para salir

 Rearrancamos

 (Fuente https://www.raspberrypi.org/forums/viewtopic.php?t=111506)
