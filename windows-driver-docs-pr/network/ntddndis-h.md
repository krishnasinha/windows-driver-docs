---
title: Ntddndis.h
author: windows-driver-content
description: This section contains kernel mode network driver topics for the Ntddndis.h header.
ms.assetid: EC2CD8C5-A2E9-4CA3-9229-BF0A955E6F53
keywords:
- Ntddndis.h network drivers
ms.author: windowsdriverdev
ms.date: 08/08/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Ntddndis.h


This section contains kernel mode network driver topics for the Ntddndis.h header. This header is included in the Windows SDK as it is also shared with user mode networking applications.

The Ntddndis.h header contains definitions for constants and types for interfacing with network drivers.

> [!IMPORTANT]
> This section's topics contains pages for definitions, macros, OIDs, status indications, and other data structures that are not part of network driver reference (structures, enumerations, functions, and callbacks). 
>
> For more information about network driver reference for this header, see [Ntddndis.h (reference)](https://msdn.microsoft.com/library/windows/hardware/mt808524).

## In this section

* [GUID_NDIS_GEN_PCI_DEVICE_CUSTOM_PROPERTIES](guid-ndis-gen-pci-device-custom-properties.md)
* [NDIS_DECLARE_SWITCH_NET_BUFFER_LIST_CONTEXT_TYPE ](ndis-declare-switch-net-buffer-list-context-type.md)
* [NDIS_MAKE_NET_LUID macro](ndis-make-net-luid.md)
* [NDIS_ROUTING_DOMAIN_ENTRY_GET_FIRST_ISOLATION_ENTRY macro](ndis-routing-domain-entry-get-first-isolation-entry.md)
* [NDIS_ROUTING_DOMAIN_ENTRY_GET_NEXT macro](ndis-routing-domain-entry-get-next.md)
* [NDIS_ROUTING_DOMAIN_ISOLATION_ENTRY_GET_NEXT macro](ndis-routing-domain-isolation-entry-get-next.md)
* [NDIS_STATUS_ISOLATION_PARAMETERS_CHANGE](ndis-status-isolation-parameters-change.md)
* [NDIS_STATUS_NIC_SWITCH_CURRENT_CAPABILITIES](ndis-status-nic-switch-current-capabilities.md)
* [NDIS_STATUS_NIC_SWITCH_HARDWARE_CAPABILITIES](ndis-status-nic-switch-hardware-capabilities.md)
* [NDIS_STATUS_RECEIVE_FILTER_QUEUE_ALLOCATION_STATE](ndis-status-receive-filter-queue-allocation-state.md)
* [NDIS_STATUS_RECEIVE_FILTER_QUEUE_PARAMETERS](ndis-status-receive-filter-queue-parameters.md)
* [NDIS_STATUS_WWAN_CONTEXT_STATE](ndis-status-wwan-context-state.md)
* [NDIS_STATUS_WWAN_HOME_PROVIDER](ndis-status-wwan-home-provider.md)
* [NDIS_STATUS_WWAN_PACKET_SERVICE](ndis-status-wwan-packet-service.md)
* [NDIS_STATUS_WWAN_PIN_INFO](ndis-status-wwan-pin-info.md)
* [NDIS_STATUS_WWAN_PIN_LIST](ndis-status-wwan-pin-list.md)
* [NDIS_STATUS_WWAN_PREFERRED_PROVIDERS](ndis-status-wwan-preferred-providers.md)
* [NDIS_STATUS_WWAN_PROVISIONED_CONTEXTS](ndis-status-wwan-provisioned-contexts.md)
* [NDIS_STATUS_WWAN_RADIO_STATE](ndis-status-wwan-radio-state.md)
* [NDIS_STATUS_WWAN_READY_INFO](ndis-status-wwan-ready-info.md)
* [NDIS_STATUS_WWAN_REGISTER_STATE](ndis-status-wwan-register-state.md)
* [NDIS_STATUS_WWAN_SERVICE_ACTIVATION](ndis-status-wwan-service-activation.md)
* [NDIS_STATUS_WWAN_SIGNAL_STATE](ndis-status-wwan-signal-state.md)
* [NDIS_STATUS_WWAN_SMS_CONFIGURATION](ndis-status-wwan-sms-configuration.md)
* [NDIS_STATUS_WWAN_SMS_DELETE](ndis-status-wwan-sms-delete.md)
* [NDIS_STATUS_WWAN_SMS_RECEIVE](ndis-status-wwan-sms-receive.md)
* [NDIS_STATUS_WWAN_SMS_SEND](ndis-status-wwan-sms-send.md)
* [NDIS_STATUS_WWAN_SMS_STATUS](ndis-status-wwan-sms-status.md)
* [NDIS_STATUS_WWAN_VENDOR_SPECIFIC](ndis-status-wwan-vendor-specific.md)
* [NDIS_STATUS_WWAN_VISIBLE_PROVIDERS](ndis-status-wwan-visible-providers.md)
* [NDIS_SWITCH_NIC_AT_ARRAY_INDEX macro](ndis-switch-nic-at-array-index.md)
* [NDIS_SWITCH_PORT_AT_ARRAY_INDEX macro](ndis-switch-port-at-array-index.md)
* [NDIS_SWITCH_PORT_PROPERTY_ROUTING_DOMAIN_GET_FIRST_ISOLATION_ENTRY macro](ndis-switch-port-property-routing-domain-get-first-isolation-entry.md)
* [NET_BUFFER_LIST_COALESCED_SEG_COUNT macro](net-buffer-list-coalesced-seg-count.md)
* [NET_BUFFER_LIST_DUP_ACK_COUNT macro](net-buffer-list-dup-ack-count.md)
* [OID_802_3_ADD_MULTICAST_ADDRESS](oid-802-3-add-multicast-address.md)
* [OID_802_3_CURRENT_ADDRESS](oid-802-3-current-address.md)
* [OID_802_3_DELETE_MULTICAST_ADDRESS](oid-802-3-delete-multicast-address.md)
* [OID_802_3_MAC_OPTIONS](oid-802-3-mac-options.md)
* [OID_802_3_MAXIMUM_LIST_SIZE](oid-802-3-maximum-list-size.md)
* [OID_802_3_MULTICAST_LIST](oid-802-3-multicast-list.md)
* [OID_802_3_PERMANENT_ADDRESS](oid-802-3-permanent-address.md)
* [OID_GEN_ADMIN_STATUS](oid-gen-admin-status.md)
* [OID_GEN_ALIAS](oid-gen-alias.md)
* [OID_GEN_BROADCAST_BYTES_RCV](oid-gen-broadcast-bytes-rcv.md)
* [OID_GEN_BROADCAST_BYTES_XMIT](oid-gen-broadcast-bytes-xmit.md)
* [OID_GEN_BROADCAST_FRAMES_RCV](oid-gen-broadcast-frames-rcv.md)
* [OID_GEN_BROADCAST_FRAMES_XMIT](oid-gen-broadcast-frames-xmit.md)
* [OID_GEN_BYTES_RCV](oid-gen-bytes-rcv.md)
* [OID_GEN_BYTES_XMIT](oid-gen-bytes-xmit.md)
* [OID_GEN_CURRENT_LOOKAHEAD](oid-gen-current-lookahead.md)
* [OID_GEN_CURRENT_PACKET_FILTER](oid-gen-current-packet-filter.md)
* [OID_GEN_DEVICE_PROFILE](oid-gen-device-profile.md)
* [OID_GEN_DIRECTED_BYTES_RCV](oid-gen-directed-bytes-rcv.md)
* [OID_GEN_DIRECTED_BYTES_XMIT](oid-gen-directed-bytes-xmit.md)
* [OID_GEN_DIRECTED_FRAMES_RCV](oid-gen-directed-frames-rcv.md)
* [OID_GEN_DIRECTED_FRAMES_XMIT](oid-gen-directed-frames-xmit.md)
* [OID_GEN_DISCONTINUITY_TIME](oid-gen-discontinuity-time.md)
* [OID_GEN_DRIVER_VERSION](oid-gen-driver-version.md)
* [OID_GEN_ENUMERATE_PORTS](oid-gen-enumerate-ports.md)
* [OID_GEN_FRIENDLY_NAME](oid-gen-friendly-name.md)
* [OID_GEN_HARDWARE_STATUS](oid-gen-hardware-status.md)
* [OID_GEN_HD_SPLIT_CURRENT_CONFIG](oid-gen-hd-split-current-config.md)
* [OID_GEN_HD_SPLIT_PARAMETERS](oid-gen-hd-split-parameters.md)
* [OID_GEN_INIT_TIME_MS](oid-gen-init-time-ms.md)
* [OID_GEN_INTERFACE_INFO](oid-gen-interface-info.md)
* [OID_GEN_INTERRUPT_MODERATION](oid-gen-interrupt-moderation.md)
* [OID_GEN_ISOLATION_PARAMETERS](oid-gen-isolation-parameters.md)
* [OID_GEN_LAST_CHANGE](oid-gen-last-change.md)
* [OID_GEN_LINK_PARAMETERS](oid-gen-link-parameters.md)
* [OID_GEN_LINK_SPEED](oid-gen-link-speed.md)
* [OID_GEN_LINK_SPEED_EX](oid-gen-link-speed-ex.md)
* [OID_GEN_LINK_STATE](oid-gen-link-state.md)
* [OID_GEN_MAC_OPTIONS](oid-gen-mac-options.md)
* [OID_GEN_MACHINE_NAME](oid-gen-machine-name.md)
* [OID_GEN_MAX_LINK_SPEED](oid-gen-max-link-speed.md)
* [OID_GEN_MAXIMUM_FRAME_SIZE](oid-gen-maximum-frame-size.md)
* [OID_GEN_MAXIMUM_LOOKAHEAD](oid-gen-maximum-lookahead.md)
* [OID_GEN_MAXIMUM_SEND_PACKETS](oid-gen-maximum-send-packets.md)
* [OID_GEN_MAXIMUM_TOTAL_SIZE](oid-gen-maximum-total-size.md)
* [OID_GEN_MEDIA_CAPABILITIES](oid-gen-media-capabilities.md)
* [OID_GEN_MEDIA_CONNECT_STATUS](oid-gen-media-connect-status.md)
* [OID_GEN_MEDIA_CONNECT_STATUS_EX](oid-gen-media-connect-status-ex.md)
* [OID_GEN_MEDIA_DUPLEX_STATE](oid-gen-media-duplex-state.md)
* [OID_GEN_MEDIA_IN_USE](oid-gen-media-in-use.md)
* [OID_GEN_MEDIA_SENSE_COUNTS](oid-gen-media-sense-counts.md)
* [OID_GEN_MEDIA_SUPPORTED](oid-gen-media-supported.md)
* [OID_GEN_MINIPORT_RESTART_ATTRIBUTES](oid-gen-miniport-restart-attributes.md)
* [OID_GEN_MULTICAST_BYTES_RCV](oid-gen-multicast-bytes-rcv.md)
* [OID_GEN_MULTICAST_BYTES_XMIT](oid-gen-multicast-bytes-xmit.md)
* [OID_GEN_MULTICAST_FRAMES_RCV](oid-gen-multicast-frames-rcv.md)
* [OID_GEN_MULTICAST_FRAMES_XMIT](oid-gen-multicast-frames-xmit.md)
* [OID_GEN_NDIS_RESERVED_1](oid-gen-ndis-reserved-1.md)
* [OID_GEN_NDIS_RESERVED_2](oid-gen-ndis-reserved-2.md)
* [OID_GEN_NDIS_RESERVED_5](oid-gen-ndis-reserved-5.md)
* [OID_GEN_NETWORK_LAYER_ADDRESSES](oid-gen-network-layer-addresses.md)
* [OID_GEN_OPERATIONAL_STATUS](oid-gen-operational-status.md)
* [OID_GEN_PCI_DEVICE_CUSTOM_PROPERTIES](oid-gen-pci-device-custom-properties.md)
* [OID_GEN_PHYSICAL_MEDIUM](oid-gen-physical-medium.md)
* [OID_GEN_PHYSICAL_MEDIUM_EX](oid-gen-physical-medium-ex.md)
* [OID_GEN_PORT_AUTHENTICATION_PARAMETERS](oid-gen-port-authentication-parameters.md)
* [OID_GEN_PORT_STATE](oid-gen-port-state.md)
* [OID_GEN_PROMISCUOUS_MODE](oid-gen-promiscuous-mode.md)
* [OID_GEN_PROTOCOL_OPTIONS](oid-gen-protocol-options.md)
* [OID_GEN_RCV_CRC_ERROR](oid-gen-rcv-crc-error.md)
* [OID_GEN_RCV_DISCARDS](oid-gen-rcv-discards.md)
* [OID_GEN_RCV_ERROR](oid-gen-rcv-error.md)
* [OID_GEN_RCV_LINK_SPEED](oid-gen-rcv-link-speed.md)
* [OID_GEN_RCV_NO_BUFFER](oid-gen-rcv-no-buffer.md)
* [OID_GEN_RCV_OK](oid-gen-rcv-ok.md)
* [OID_GEN_RECEIVE_BLOCK_SIZE](oid-gen-receive-block-size.md)
* [OID_GEN_RECEIVE_BUFFER_SPACE](oid-gen-receive-buffer-space.md)
* [OID_GEN_RECEIVE_HASH](oid-gen-receive-hash.md)
* [OID_GEN_RECEIVE_SCALE_CAPABILITIES](oid-gen-receive-scale-capabilities.md)
* [OID_GEN_RECEIVE_SCALE_PARAMETERS](oid-gen-receive-scale-parameters.md)
* [OID_GEN_RESET_COUNTS](oid-gen-reset-counts.md)
* [OID_GEN_RNDIS_CONFIG_PARAMETER](oid-gen-rndis-config-parameter.md)
* [OID_GEN_STATISTICS](oid-gen-statistics.md)
* [OID_GEN_SUPPORTED_GUIDS](oid-gen-supported-guids.md)
* [OID_GEN_SUPPORTED_LIST](oid-gen-supported-list.md)
* [OID_GEN_SUPPORTED_PACKET_FILTERS](oid-gen-supported-packet-filters.md)
* [OID_GEN_TRANSMIT_BLOCK_SIZE](oid-gen-transmit-block-size.md)
* [OID_GEN_TRANSMIT_BUFFER_SPACE](oid-gen-transmit-buffer-space.md)
* [OID_GEN_TRANSMIT_QUEUE_LENGTH](oid-gen-transmit-queue-length.md)
* [OID_GEN_TRANSPORT_HEADER_OFFSET](oid-gen-transport-header-offset.md)
* [OID_GEN_UNKNOWN_PROTOS](oid-gen-unknown-protos.md)
* [OID_GEN_VENDOR_ID](oid-gen-vendor-id.md)
* [OID_GEN_VLAN_ID](oid-gen-vlan-id.md)
* [OID_GEN_XMIT_DISCARDS](oid-gen-xmit-discards.md)
* [OID_GEN_XMIT_ERROR](oid-gen-xmit-error.md)
* [OID_GEN_XMIT_LINK_SPEED](oid-gen-xmit-link-speed.md)
* [OID_GEN_XMIT_OK](oid-gen-xmit-ok.md)
* [OID_NDK_CONNECTIONS](oid-ndk-connections.md)
* [OID_NDK_LOCAL_ENDPOINTS](oid-ndk-local-endpoints.md)
* [OID_NDK_SET_STATE](oid-ndk-set-state.md)
* [OID_NDK_STATISTICS](oid-ndk-statistics.md)
* [OID_NIC_SWITCH_ALLOCATE_VF](oid-nic-switch-allocate-vf.md)
* [OID_NIC_SWITCH_CREATE_SWITCH](oid-nic-switch-create-switch.md)
* [OID_NIC_SWITCH_CREATE_VPORT](oid-nic-switch-create-vport.md)
* [OID_NIC_SWITCH_CURRENT_CAPABILITIES](oid-nic-switch-current-capabilities.md)
* [OID_NIC_SWITCH_DELETE_SWITCH](oid-nic-switch-delete-switch.md)
* [OID_NIC_SWITCH_DELETE_VPORT](oid-nic-switch-delete-vport.md)
* [OID_NIC_SWITCH_ENUM_SWITCHES](oid-nic-switch-enum-switches.md)
* [OID_NIC_SWITCH_ENUM_VFS](oid-nic-switch-enum-vfs.md)
* [OID_NIC_SWITCH_ENUM_VPORTS](oid-nic-switch-enum-vports.md)
* [OID_NIC_SWITCH_FREE_VF](oid-nic-switch-free-vf.md)
* [OID_NIC_SWITCH_HARDWARE_CAPABILITIES](oid-nic-switch-hardware-capabilities.md)
* [OID_NIC_SWITCH_PARAMETERS](oid-nic-switch-parameters.md)
* [OID_NIC_SWITCH_VF_PARAMETERS](oid-nic-switch-vf-parameters.md)
* [OID_NIC_SWITCH_VPORT_PARAMETERS](oid-nic-switch-vport-parameters.md)
* [OID_PACKET_COALESCING_FILTER_MATCH_COUNT](oid-packet-coalescing-filter-match-count.md)
* [OID_PD_CLOSE_PROVIDER](oid-pd-close-provider.md)
* [OID_PD_OPEN_PROVIDER](oid-pd-open-provider.md)
* [OID_PD_QUERY_CURRENT_CONFIG](oid-pd-query-current-config.md)
* [OID_PM_ADD_PROTOCOL_OFFLOAD](oid-pm-add-protocol-offload.md)
* [OID_PM_ADD_WOL_PATTERN](oid-pm-add-wol-pattern.md)
* [OID_PM_CURRENT_CAPABILITIES](oid-pm-current-capabilities.md)
* [OID_PM_GET_PROTOCOL_OFFLOAD](oid-pm-get-protocol-offload.md)
* [OID_PM_HARDWARE_CAPABILITIES](oid-pm-hardware-capabilities.md)
* [OID_PM_PARAMETERS](oid-pm-parameters.md)
* [OID_PM_PROTOCOL_OFFLOAD_LIST](oid-pm-protocol-offload-list.md)
* [OID_PM_REMOVE_PROTOCOL_OFFLOAD](oid-pm-remove-protocol-offload.md)
* [OID_PM_REMOVE_WOL_PATTERN](oid-pm-remove-wol-pattern.md)
* [OID_PM_WOL_PATTERN_LIST](oid-pm-wol-pattern-list.md)
* [OID_PNP_ADD_WAKE_UP_PATTERN](oid-pnp-add-wake-up-pattern.md)
* [OID_PNP_CAPABILITIES](oid-pnp-capabilities.md)
* [OID_PNP_ENABLE_WAKE_UP](oid-pnp-enable-wake-up.md)
* [OID_PNP_QUERY_POWER](oid-pnp-query-power.md)
* [OID_PNP_REMOVE_WAKE_UP_PATTERN](oid-pnp-remove-wake-up-pattern.md)
* [OID_PNP_SET_POWER](oid-pnp-set-power.md)
* [OID_PNP_WAKE_UP_ERROR](oid-pnp-wake-up-error.md)
* [OID_PNP_WAKE_UP_OK](oid-pnp-wake-up-ok.md)
* [OID_PNP_WAKE_UP_PATTERN_LIST](oid-pnp-wake-up-pattern-list.md)
* [OID_QOS_CURRENT_CAPABILITIES](oid-qos-current-capabilities.md)
* [OID_QOS_HARDWARE_CAPABILITIES](oid-qos-hardware-capabilities.md)
* [OID_QOS_OPERATIONAL_PARAMETERS](oid-qos-operational-parameters.md)
* [OID_QOS_PARAMETERS](oid-qos-parameters.md)
* [OID_QOS_REMOTE_PARAMETERS](oid-qos-remote-parameters.md)
* [OID_RECEIVE_FILTER_ALLOCATE_QUEUE](oid-receive-filter-allocate-queue.md)
* [OID_RECEIVE_FILTER_CLEAR_FILTER](oid-receive-filter-clear-filter.md)
* [OID_RECEIVE_FILTER_CURRENT_CAPABILITIES](oid-receive-filter-current-capabilities.md)
* [OID_RECEIVE_FILTER_ENUM_FILTERS](oid-receive-filter-enum-filters.md)
* [OID_RECEIVE_FILTER_ENUM_QUEUES](oid-receive-filter-enum-queues.md)
* [OID_RECEIVE_FILTER_FREE_QUEUE](oid-receive-filter-free-queue.md)
* [OID_RECEIVE_FILTER_GLOBAL_PARAMETERS](oid-receive-filter-global-parameters.md)
* [OID_RECEIVE_FILTER_HARDWARE_CAPABILITIES](oid-receive-filter-hardware-capabilities.md)
* [OID_RECEIVE_FILTER_MOVE_FILTER](oid-receive-filter-move-filter.md)
* [OID_RECEIVE_FILTER_PARAMETERS](oid-receive-filter-parameters.md)
* [OID_RECEIVE_FILTER_QUEUE_ALLOCATION_COMPLETE](oid-receive-filter-queue-allocation-complete.md)
* [OID_RECEIVE_FILTER_QUEUE_PARAMETERS](oid-receive-filter-queue-parameters.md)
* [OID_RECEIVE_FILTER_SET_FILTER](oid-receive-filter-set-filter.md)
* [OID_SRIOV_BAR_RESOURCES](oid-sriov-bar-resources.md)
* [OID_SRIOV_CURRENT_CAPABILITIES](oid-sriov-current-capabilities.md)
* [OID_SRIOV_HARDWARE_CAPABILITIES](oid-sriov-hardware-capabilities.md)
* [OID_SRIOV_PF_LUID](oid-sriov-pf-luid.md)
* [OID_SRIOV_PROBED_BARS](oid-sriov-probed-bars.md)
* [OID_SRIOV_READ_VF_CONFIG_BLOCK](oid-sriov-read-vf-config-block.md)
* [OID_SRIOV_READ_VF_CONFIG_SPACE](oid-sriov-read-vf-config-space.md)
* [OID_SRIOV_RESET_VF](oid-sriov-reset-vf.md)
* [OID_SRIOV_SET_VF_POWER_STATE](oid-sriov-set-vf-power-state.md)
* [OID_SRIOV_VF_INVALIDATE_CONFIG_BLOCK](oid-sriov-vf-invalidate-config-block.md)
* [OID_SRIOV_VF_SERIAL_NUMBER](oid-sriov-vf-serial-number.md)
* [OID_SRIOV_VF_VENDOR_DEVICE_ID](oid-sriov-vf-vendor-device-id.md)
* [OID_SRIOV_WRITE_VF_CONFIG_BLOCK](oid-sriov-write-vf-config-block.md)
* [OID_SRIOV_WRITE_VF_CONFIG_SPACE](oid-sriov-write-vf-config-space.md)
* [OID_SWITCH_FEATURE_STATUS_QUERY](oid-switch-feature-status-query.md)
* [OID_SWITCH_NIC_ARRAY](oid-switch-nic-array.md)
* [OID_SWITCH_NIC_CONNECT](oid-switch-nic-connect.md)
* [OID_SWITCH_NIC_CREATE](oid-switch-nic-create.md)
* [OID_SWITCH_NIC_DELETE](oid-switch-nic-delete.md)
* [OID_SWITCH_NIC_DISCONNECT](oid-switch-nic-disconnect.md)
* [OID_SWITCH_NIC_REQUEST](oid-switch-nic-request.md)
* [OID_SWITCH_NIC_RESTORE](oid-switch-nic-restore.md)
* [OID_SWITCH_NIC_RESTORE_COMPLETE](oid-switch-nic-restore-complete.md)
* [OID_SWITCH_NIC_SAVE](oid-switch-nic-save.md)
* [OID_SWITCH_NIC_SAVE_COMPLETE](oid-switch-nic-save-complete.md)
* [OID_SWITCH_NIC_UPDATED](oid-switch-nic-updated.md)
* [OID_SWITCH_PARAMETERS](oid-switch-parameters.md)
* [OID_SWITCH_PORT_ARRAY](oid-switch-port-array.md)
* [OID_SWITCH_PORT_CREATE](oid-switch-port-create.md)
* [OID_SWITCH_PORT_DELETE](oid-switch-port-delete.md)
* [OID_SWITCH_PORT_FEATURE_STATUS_QUERY](oid-switch-port-feature-status-query.md)
* [OID_SWITCH_PORT_PROPERTY_ADD](oid-switch-port-property-add.md)
* [OID_SWITCH_PORT_PROPERTY_DELETE](oid-switch-port-property-delete.md)
* [OID_SWITCH_PORT_PROPERTY_ENUM](oid-switch-port-property-enum.md)
* [OID_SWITCH_PORT_PROPERTY_UPDATE](oid-switch-port-property-update.md)
* [OID_SWITCH_PORT_TEARDOWN](oid-switch-port-teardown.md)
* [OID_SWITCH_PORT_UPDATED](oid-switch-port-updated.md)
* [OID_SWITCH_PROPERTY_ADD](oid-switch-property-add.md)
* [OID_SWITCH_PROPERTY_DELETE](oid-switch-property-delete.md)
* [OID_SWITCH_PROPERTY_ENUM](oid-switch-property-enum.md)
* [OID_SWITCH_PROPERTY_UPDATE](oid-switch-property-update.md)
* [OID_TCP_RSC_STATISTICS](oid-tcp-rsc-statistics.md)
* [OID_TCP_TASK_IPSEC_OFFLOAD_V2_ADD_SA](oid-tcp-task-ipsec-offload-v2-add-sa.md)
* [OID_TCP_TASK_IPSEC_OFFLOAD_V2_ADD_SA_EX](oid-tcp-task-ipsec-offload-v2-add-sa-ex.md)
* [OID_TCP_TASK_IPSEC_OFFLOAD_V2_DELETE_SA](oid-tcp-task-ipsec-offload-v2-delete-sa.md)
* [OID_TCP_TASK_IPSEC_OFFLOAD_V2_UPDATE_SA](oid-tcp-task-ipsec-offload-v2-update-sa.md)
* [OID_WAN_CO_GET_COMP_INFO](oid-wan-co-get-comp-info.md)
* [OID_WAN_CO_GET_INFO](oid-wan-co-get-info.md)
* [OID_WAN_CO_GET_LINK_INFO](oid-wan-co-get-link-info.md)
* [OID_WAN_CO_GET_STATS_INFO](oid-wan-co-get-stats-info.md)
* [OID_WAN_CO_SET_COMP_INFO](oid-wan-co-set-comp-info.md)
* [OID_WAN_CO_SET_LINK_INFO](oid-wan-co-set-link-info.md)
* [OID_WWAN_AUTH_CHALLENGE](oid-wwan-auth-challenge.md)
* [OID_WWAN_CONNECT](oid-wwan-connect.md)
* [OID_WWAN_CREATE_MAC](oid-wwan-create-mac.md)
* [OID_WWAN_DELETE_MAC](oid-wwan-delete-mac.md)
* [OID_WWAN_DEVICE_CAPS](oid-wwan-device-caps.md)
* [OID_WWAN_DEVICE_CAPS_EX](oid-wwan-device-caps-ex.md)
* [OID_WWAN_DEVICE_SERVICE_COMMAND](oid-wwan-device-service-command.md)
* [OID_WWAN_DEVICE_SERVICE_SESSION](oid-wwan-device-service-session.md)
* [OID_WWAN_DEVICE_SERVICE_SESSION_WRITE](oid-wwan-device-service-session-write.md)
* [OID_WWAN_DEVICE_SERVICES](oid-wwan-device-services.md)
* [OID_WWAN_DEVICE_SLOT_MAPPING_INFO](oid-wwan-device-slot-mappings.md)
* [OID_WWAN_DRIVER_CAPS](oid-wwan-driver-caps.md)
* [OID_WWAN_ENUMERATE_DEVICE_SERVICE_COMMANDS](oid-wwan-enumerate-device-service-commands.md)
* [OID_WWAN_ENUMERATE_DEVICE_SERVICES](oid-wwan-enumerate-device-services.md)
* [OID_WWAN_HOME_PROVIDER](oid-wwan-home-provider.md)
* [OID_WWAN_NETWORK_IDLE_HINT](oid-wwan-network-idle-hint.md)
* [OID_WWAN_PACKET_SERVICE](oid-wwan-packet-service.md)
* [OID_WWAN_PIN](oid-wwan-pin.md)
* [OID_WWAN_PIN_EX](oid-wwan-pin-ex.md)
* [OID_WWAN_PIN_LIST](oid-wwan-pin-list.md)
* [OID_WWAN_PREFERRED_MULTICARRIER_PROVIDERS](oid-wwan-preferred-multicarrier-providers.md)
* [OID_WWAN_PREFERRED_PROVIDERS](oid-wwan-preferred-providers.md)
* [OID_WWAN_PRESHUTDOWN](oid-wwan-preshutdown.md)
* [OID_WWAN_PROVISIONED_CONTEXTS](oid-wwan-provisioned-contexts.md)
* [OID_WWAN_RADIO_STATE](oid-wwan-radio-state.md)
* [OID_WWAN_READY_INFO](oid-wwan-ready-info.md)
* [OID_WWAN_REGISTER_STATE](oid-wwan-register-state.md)
* [OID_WWAN_SERVICE_ACTIVATION](oid-wwan-service-activation.md)
* [OID_WWAN_SIGNAL_STATE](oid-wwan-signal-state.md)
* [OID_WWAN_SLOT_INFO](oid-wwan-slot-info-status.md)
* [OID_WWAN_SMS_CONFIGURATION](oid-wwan-sms-configuration.md)
* [OID_WWAN_SMS_DELETE](oid-wwan-sms-delete.md)
* [OID_WWAN_SMS_READ](oid-wwan-sms-read.md)
* [OID_WWAN_SMS_SEND](oid-wwan-sms-send.md)
* [OID_WWAN_SMS_STATUS](oid-wwan-sms-status.md)
* [OID_WWAN_SUBSCRIBE_DEVICE_SERVICE_EVENTS](oid-wwan-subscribe-device-service-events.md)
* [OID_WWAN_SYS_CAPS_INFO](oid-wwan-sys-caps.md)
* [OID_WWAN_USSD](oid-wwan-ussd.md)
* [OID_WWAN_VENDOR_SPECIFIC](oid-wwan-vendor-specific.md)
* [OID_WWAN_VISIBLE_PROVIDERS](oid-wwan-visible-providers.md)

--------------------
[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bnetvista\netvista%5D:%20Ntddndis.h%20%20RELEASE:%20%288/3/2017%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")


