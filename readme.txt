===============================================================================
		Software Package - Component
===============================================================================
	1. ReleaseNotes.pdf

	2. document/
		2.1. Driver_Configuration_for_RF_Regulatory_Certification.pdf
		2.2. How_to_append_vendor_specific_ie_to_driver_management_frames.pdf
		2.3. HowTo_enable_and_verify_TDLS_function_in_Wi-Fi_driver.pdf
		2.4. HowTo_enable_driver_to_support_80211d.pdf
		2.5. How_to_enable_Realtek_RSON_function.pdf
		2.6. HowTo_enable_the_power_saving_functionality.pdf
		2.7. HowTo_port_wireless_driver_to_Google_ChromiumOS.pdf
		2.8. How_to_set_driver_debug_log_level.pdf
		2.9. HowTo_support_WIFI_certification_test.pdf
		2.10. linux_dhcp_server_notes.txt
		2.11. Miracast_for_Realtek_WiFi.pdf
		2.12. Quick_Start_Guide_for_Adaptivity_and_Carrier_Sensing_Test.pdf
		2.13. Quick_Start_Guide_for_Bridge.pdf
		2.14. Quick_Start_Guide_for_Driver_Compilation_and_Installation.pdf
		2.15. Quick_Start_Guide_for_SoftAP.pdf
		2.16. Quick_Start_Guide_for_Station_Mode.pdf
		2.17. Quick_Start_Guide_for_WOW.pdf
		2.18. Quick_Start_Guide_for_WPA3.pdf
		2.19. Quick_Start_Guide_for_wpa_supplicant_WiFi_P2P_test.pdf
		2.20. Realtek_WiFi_concurrent_mode_Introduction.pdf
		2.21. RTK_P2P_WFD_Programming_guide.pdf
		2.22. SoftAP_Mode_features.pdf
		2.23. Wireless_tools_porting_guide.pdf
		2.24. wpa_cli_with_wpa_supplicant.pdf

	3. driver/
		3.1. rtl88x2CE_WiFi_linux_v5.9.0_36003.20200220_COEX20191120-1515.tar.gz
			Naming rule: rtlCHIPS[_WiFi]_linux_vM.N.P[.H]_sssss.yyyymmdd[_COEX_VER][_beta].tar.gz
			where:
				CHIPS: supported chips
				M: Major version
				N: miNor version
				P: Patch number
				H: Hotfix number
				s: SVN number
				y: package year
				m: package month
				d: package day
				COEX_VER: Coext version
				_beta: beta driver

	4. android_ref_codes_KK_4.4/
		4.1. linux-3.0.42_STATION_INFO_ASSOC_REQ_IES.diff
			Kernel patch file for cfg80211's STATION_INFO_ASSOC_REQ_IES event for kernel 3.0.

		4.2. realtek_wifi_SDK_for_android_KK_4.4_20140117.tar.gz
			This tar ball includes our android wifi reference codes for Android 4.4

		4.3. Realtek_Wi-Fi_SDK_for_Android_KK_4.4.pdf
			Guide for porting Realtek wifi onto your Android 4.4 system

	5. android_ref_codes_M_6.x/
		5.1. linux-3.0.42_STATION_INFO_ASSOC_REQ_IES.diff
			Kernel patch file for cfg80211's STATION_INFO_ASSOC_REQ_IES event for kernel 3.0.

		5.2. realtek_wifi_SDK_for_android_M_6.x_20151116.tgz
			This tar ball includes our android wifi reference codes for Android 6.x

		5.3. Realtek_Wi-Fi_SDK_for_Android_M_6.x.pdf
			Guide for porting Realtek wifi onto your Android 6.x system

	6. android_ref_codes_N_7.0/
		6.1. linux-3.0.42_STATION_INFO_ASSOC_REQ_IES.diff
			Kernel patch file for cfg80211's STATION_INFO_ASSOC_REQ_IES event for kernel 3.0.

		6.2. realtek_wifi_SDK_for_android_N_7.0_20161024.zip
			This tar ball includes our android wifi reference codes for Android 7.0

		6.3. Realtek_Wi-Fi_SDK_for_Android_N_7.0.pdf
			Guide for porting Realtek wifi onto your Android 7.0 system

	7. android_ref_codes_O_8.0/
		7.1. linux-3.0.42_STATION_INFO_ASSOC_REQ_IES.diff
			Kernel patch file for cfg80211's STATION_INFO_ASSOC_REQ_IES event for kernel 3.0.

		7.2. realtek_wifi_SDK_for_android_O_8.0_20181001.tar.gz
			This tar ball includes our android wifi reference codes for Android 8.0

		7.3. Realtek_Wi-Fi_SDK_for_Android_O_8.0.pdf
			Guide for porting Realtek wifi onto your Android 8.0 system

		7.4. supplicant_overlay_config.tar.gz

	8. android_ref_codes_P_9.x/
		8.1. linux-3.0.42_STATION_INFO_ASSOC_REQ_IES.diff
			Kernel patch file for cfg80211's STATION_INFO_ASSOC_REQ_IES event for kernel 3.0.

		8.2. realtek_wifi_SDK_for_android_P_9.x_20190827.tar.gz
			This tar ball includes our android wifi reference codes for Android 9.x

		8.3. Realtek_Wi-Fi_SDK_for_Android_P_9.x.pdf
			Guide for porting Realtek wifi onto your Android 9.x system

		8.4. supplicant_overlay_config.tar.gz

	9. android_ref_codes_10.x/
		9.1. wpa_supplicant_8_10.x_rtw_29226.20191002.tgz
			wpa_supplicant_8 from Android 10.x SDK and patched by Realtek
			could be used Android 10.x. Support only cfg80211/nl80211.

		9.2. Realtek_Wi-Fi_SDK_for_Android_10.pdf
			Guide for porting Realtek wifi onto your Android 10.x system

		9.3. realtek_wifi_SDK_for_android_10_x_20191008.tgz
			This tar ball includes our android wifi reference codes for Android 10.x

		9.4. supplicant_overlay_config.tar.gz

	10. btcoex/
		10.1. HowTo_debug_BT_coexistence.pdf
			Guide for debug BT coexistence

		10.2. How_to_set_bt-coex_antenna_isolation_parameters_on_combo_card.pdf
			Guide for setting bt-coex antenna isolation parameters on combo card module

		10.3. script/
			10.3.1. btcoex_lnx.sh
				BT coexistence debug tools for Linux platform

			10.3.2. btcoex_win.bat
				BT coexistence debug tools for Android platform on Windows PC

		10.4. wifi_ant_isolation.txt
			Configure file example

	11. hardware_wps_pbc/
		11.1. Readme.txt

		11.2. sample.c

	12. install.sh
		Script to compile and install WiFi driver easily in PC-Linux

	13. wake_on_wlan_tool/
	14. wireless_tools/
		14.1. wireless_tools.30.rtl.tar.gz

	15. wpa_supplicant_hostapd/
		15.1. wpa_supplicant_8_kk_4.4_rtw_r25669.20171213.tar.gz
			wpa_supplicant_8 from Android 4.4 SDK and patched by Realtek
			could be used for pure-linux and Android 4.4. Support only cfg80211/nl80211.

		15.2. wpa_supplicant_8_M_6.x_rtw_r24570.20171025.tar.gz
			wpa_supplicant_8 from Android 6.x SDK and patched by Realtek
			could be used for pure-linux and Android 6.x. Support only cfg80211/nl80211.

		15.3. wpa_supplicant_8_N_7.x_rtw_r24577.20171025.tar.gz
			wpa_supplicant_8 from Android 7.x SDK and patched by Realtek
			could be used for pure-linux and Android 7.x. Support only cfg80211/nl80211.

		15.4. wpa_supplicant_8_O_8.x_rtw-2-g461faa34d.20191121.tar.gz
			wpa_supplicant_8 from Android 8.x SDK and patched by Realtek
			could be used for pure-linux and Android 8.x. Support only cfg80211/nl80211.

		15.5. wpa_supplicant_8_P_9.x_rtw_r29226.20180827.tar.gz
			wpa_supplicant_8 from Android 9.x SDK and patched by Realtek
			could be used Android 9.x. Support only cfg80211/nl80211.

		15.6. p2p_hostapd.conf
			Configure file for hostapd for Wi-Fi Direct (P2P)

		15.7. rtl_hostapd_2G.conf
			Configure files for Soft-AP mode 2.4G

		15.8. rtl_hostapd_5G.conf
			Configure files for Soft-AP mode 5G

		15.9. wpa_0_8.conf
			Configure file sample for wpa_supplicant-0.8

		15.10. wpa_supplicant_hostapd-0.8_rtw_r24647.20171025.tar.gz
			15.10.1 wpa_supplicant
				The tool help the wlan network to communicate under the
				protection of WPAPSK mechanism (WPA/WPA2) and add WPS patch

			15.10.2 hostapd

==================================================================================================================
		User Guide for Driver compilation and installation
==================================================================================================================
			(*) Please refer to document/Quick_Start_Guide_for_Driver_Compilation_and_Installation.pdf
==================================================================================================================
		User Guide for Station mode
==================================================================================================================
			(*) Please refer to document/Quick_Start_Guide_for_Station_Mode.pdf
==================================================================================================================
		User Guide for Soft-AP mode
==================================================================================================================
			(*) Please refer to document/Quick_Start_Guide_for_SoftAP.pdf
			(*) Please use wpa_supplicant_hostapd-0.8_rtw_r24647.20171025.tar.gz
			(*) Please refer to document/linux_dhcp_server_notes.txt
==================================================================================================================
		User Guide for Wi-Fi Direct
==================================================================================================================
		Realtek Legacy Wi-Fi Direct:
			(*) Please refer to document/RTK_P2P_WFD_Programming_guide.pdf
			(*) Please use wpa_supplicant_hostapd-0.8_rtw_r24647.20171025.tar.gz
			(*) Please refer to document/linux_dhcp_server_notes.txt
		Wi-Fi Direct with nl80211
			(*) Please use:
					wpa_supplicant_8_kk_4.4_rtw_r25669.20171213.tar.gz
				or
					wpa_supplicant_8_M_6.x_rtw_r24570.20171025.tar.gz
				or
					wpa_supplicant_8_N_7.x_rtw_r24577.20171025.tar.gz
				or
					wpa_supplicant_8_O_8.x_rtw-2-g461faa34d.20191121.tar.gz
				or
					wpa_supplicant_8_P_9.x_rtw_r29226.20180827.tar.gz
				or
					wpa_supplicant_8_10.x_rtw_29226.20191002.tgz
			(*) For P2P instruction/command, please refer to:
					README-P2P inside the wpa_supplicant folder of the wpa_supplicant_8 you choose
			(*) For DHCP server, please refer to:
					document/linux_dhcp_server_notes.txt
==================================================================================================================
		User Guide for WPS2.0
==================================================================================================================
			(*) Please use:
					wpa_supplicant_hostapd-0.8_rtw_r24647.20171025.tar.gz
				or
					wpa_supplicant_8_kk_4.4_rtw_r25669.20171213.tar.gz
				or
					wpa_supplicant_8_M_6.x_rtw_r24570.20171025.tar.gz
				or
					wpa_supplicant_8_N_7.x_rtw_r24577.20171025.tar.gz
				or
					wpa_supplicant_8_O_8.x_rtw-2-g461faa34d.20191121.tar.gz
				or
					wpa_supplicant_8_P_9.x_rtw_r29226.20180827.tar.gz
				or
					wpa_supplicant_8_10.x_rtw_29226.20191002.tgz
			(*) For WPS instruction/command, please refert to:
					README-WPS inside the wpa_supplicant folder of the wpa_supplicant_8 you choose
==================================================================================================================
		User Guide for Power Saving Mode
==================================================================================================================
			(*) Please refer to document/HowTo_enable_the_power_saving_functionality.pdf
==================================================================================================================
		User Guide for Applying Wi-Fi solution onto Andriod System
==================================================================================================================
			(*) For Android 4.4, please refer to android_ref_codes_KK_4.4/Realtek_Wi-Fi_SDK_for_Android_KK_4.4.pdf
			(*) For Android 6.x, please refer to android_ref_codes_M_6.x/Realtek_Wi-Fi_SDK_for_Android_M_6.x.pdf
			(*) For Android 7.0, please refer to android_ref_codes_N_7.0/Realtek_Wi-Fi_SDK_for_Android_N_7.0.pdf
			(*) For Android 8.0, please refer to android_ref_codes_O_8.0/Realtek_Wi-Fi_SDK_for_Android_O_8.0.pdf
			(*) For Android 9.x, please refer to android_ref_codes_P_9.x/Realtek_Wi-Fi_SDK_for_Android_P_9.x.pdf
			(*) For Android 10.x, please refer to android_ref_codes_10.x/Realtek_Wi-Fi_SDK_for_Android_10.pdf
==================================================================================================================
		User Guide for WPA3 Personal
==================================================================================================================
			(*) wpa_supplicant_8_O_8.x_rtw-2-g461faa34d.20191121.tar.gz
			(*) Please refer to wpa_cli_with_wpa_supplicant.pdf
			(*) Please refer to Quick_Start_Guide_for_WPA3.pdf