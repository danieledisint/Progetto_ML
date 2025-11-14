These attributes are related to the characteristics of a network connection. Feature prefixed with _c_ or _s_,  stands for "client" and "server", respectively. Here is a list of the attributes and a brief description of each:

_c_ack_cnt: The number of ACK packets sent by the client.
_c_ack_cnt_p: The percentage of ACK packets sent by the client.
_c_appdataB: The number of bytes of application data sent by the client. 
_c_appdataT: The number of packets of application data sent by the client. 
_c_bytes_all: The total number of bytes sent by the client.
_c_bytes_retx: The number of bytes of retransmitted data sent by the client.
_c_bytes_uniq: The number of unique bytes sent by the client.
_c_cwin_ini: The initial congestion window size for the client.
_c_cwin_max: The maximum congestion window size for the client.
_c_cwin_min: The minimum congestion window size for the client.
_c_fin_cnt: The number of FIN packets sent by the client.
_c_first: The time of the first packet sent by the client.
_c_first_ack: The time of the first ACK packet sent by the client.
_c_last: The time of the last packet sent by the client.
_c_last_handshakeT: The time of the last handshake packet sent by the client. 
_c_msgsize1: The size of the first message sent by the client.
_c_msgsize_count: The number of message sizes sent by the client.
_c_mss: The maximum segment size (MSS) for the client.
_c_mss_max: The maximum MSS for the client.
_c_mss_min: The minimum MSS for the client.
_c_pkts_all: The total number of packets sent by the client.
_c_pkts_data: The number of data packets sent by the client.
_c_pkts_data_avg: The average number of data packets sent by the client. 
_c_pkts_data_std: The standard deviation of the number of data packets sent by the client. 
_c_pkts_dup: The number of duplicate packets sent by the client.
_c_pkts_fc: Number of retransmitted segments to probe the receiver window
_c_pkts_ooo: The number of out-of-order packets sent by the client.
_c_pkts_push: The number of PUSH packets sent by the client.
_c_pkts_reor: The number of reordered packets sent by the client.
_c_pkts_retx: Number of retransmitted packets sent by the client.
_c_pkts_rto: Number of packets sent by the client that triggered a retransmission timeout.
_c_pkts_unfs: Number of packets sent by the client with the FIN flag set but without ACK
_c_pkts_unk: Number of segments not in sequence or duplicate which are not classified as specific events
_c_pkts_unrto': Number of packets sent by the client that caused a retransmission timeout to be cancelled.
_c_pktsize1: Size of the first packet sent by the client.
_c_pktsize_count: Number of packets sizes sent by the client.
_c_port: Port number used by the client.
_c_rst_cnt: Number of reset (RST) packets sent by the client.
_c_rtt_avg: Average round-trip time (RTT) for packets sent by the client.
_c_rtt_cnt: Number of RTT measurements for packets sent by the client.
_c_rtt_max: Maximum RTT for packets sent by the client.
_c_rtt_min: Minimum RTT for packets sent by the client.
_c_rtt_std: Standard deviation of the RTT for packets sent by the client.
_c_sack_cnt: Number of selective acknowledgement (SACK) packets sent by the client.
_c_sack_opt: Indicates whether the client supports SACK.
_c_seg_cnt: Number of segments sent by the client.
_c_sit1: Size of the first segment sent by the client.
_c_sit_avg: Average size of segments sent by the client.
_c_sit_std: Standard deviation of the size of segments sent by the client.
_c_syn_cnt: Number of SYN (synchronize) packets sent by the client.
_c_syn_retx: Number of SYN packets retransmitted by the client.
_c_tm_opt: Indicates whether the client supports the TCP timeout option.
_c_ttl_max: Maximum time-to-live (TTL) value used by the client.
_c_ttl_min: Minimum TTL value used by the client.
_c_win_0: Number of times the congestion window size was zero for the client.
_c_win_max: Maximum congestion window size for the client.
_c_win_min: Minimum congestion window size for the client.
_c_win_scl: Window scaling factor used by the client.
_durat: Duration of the connections.
_s_ack_cnt: Number of acknowledgement packets sent by the server.
_s_ack_cnt_p: Percentage of packets sent by the server that are acknowledgement packets.
_s_appdataB: Number of bytes of application data sent by the server.
_s_appdataT: Number of packets containing application data sent by the server.
_s_bytes_all: Total number of bytes sent by the server.
_s_bytes_retx: Number of bytes retransmitted by the server.
_s_bytes_uniq: Number of unique bytes sent by the server.
_s_bytes_uniq: Number of unique bytes sent by the server.
_s_cwin_ini: Initial congestion window size used by the server.
_s_cwin_max: Maximum congestion window size used by the server.
_s_cwin_min: Minimum congestion window size used by the server.
_s_f1323_opt: Indicates whether the server supports the TCP options for window scaling, selective  acknowledgement, and timestamps (also known as "TCP congestion control").
_s_fin_cnt: Number of FIN (end-of-connection) packets sent by the server.
_s_first: Timestamp of the first packet sent by the server.
_s_first_ack: Timestamp of the first acknowledgement packet sent by the server.
_s_last: Timestamp of the last packet sent by the server.
_s_last_handshakeT: the time of the last handshake packet sent by the server. 
_s_msgsize1: Size of the first message sent by the server.
_s_msgsize_count: Number of messages sent by the server.
_s_mss: Maximum segment size used by the server.
_s_mss_max: Maximum MSS value used by the server.
_s_mss_min: Minimum MSS value used by the server.
_s_pkts_all: Total number of packets sent by the server.
_s_pkts_data: Number of data packets sent by the server.
_s_pkts_data_avg: Average number of data packets sent by the server per message.
_s_pkts_data_std: Standard deviation of the number of data packets sent by the server per message.
_s_pkts_dup: Number of duplicate packets sent by the server.
_s_pkts_fc: Number of flow control packets sent by the server.
_s_pkts_fs: Number of packets with the FIN/SYN flag set sent by the server.
_s_pkts_ooo: Number of out-of-order packets sent by the server.
_s_pkts_push: Number of push packets sent by the server.
_s_pkts_reor: Number of packets sent by the server that caused reordering.
_s_pkts_retx: Number of retransmitted packets sent by the server.
_s_pkts_rto: Number of packets sent by the server that caused a retransmission timeout.
_s_pkts_unfs: Number of unfragmented packets sent by the server.
_s_pkts_unk: Number of unknown packets sent by the server.
_s_pkts_unrto: Number of packets sent by the server that caused a retransmission timeout to be cancelled.
_s_pktsize1: Size of the first packet sent by the server.
_s_pktsize_count: Number of packets sent by the server.
_s_port: Port number used by the server.
_s_rst_cnt: Number of reset (RST) packets sent by the server.
_s_rtt_avg: Average round-trip time (RTT) for packets sent by the server.
_s_rtt_cnt: Number of RTT measurements for packets sent by the server.
_s_rtt_max: Maximum RTT for packets sent by the server.
_s_rtt_min: Minimum RTT for packets sent by the server.
_s_rtt_std: Standard deviation of the RTT for packets sent by the server.
_s_sack_cnt: Number of selective acknowledgement (SACK) packets sent by the server.
_s_sack_opt: Indicates whether the server supports SACK.
_s_seg_cnt: Number of segments sent by the server.
_s_sit1: Size of the first segment sent by the server.
_s_sit_avg: Average size of segments sent by the server.
_s_sit_std: Standard deviation of the size of segments sent by the server.
_s_syn_cnt: Number of SYN (synchronize) packets sent by the server.
_s_syn_retx: Number of SYN packets retransmitted by the server.
_s_tm_opt: Indicates whether the server supports the TCP timestamp option.
_s_ttl_max: Maximum time-to-live (TTL) value used by the server.
_s_ttl_min: Minimum TTL value used by the server.
_s_win_0: Number of zero-sized window updates sent by the server.
_s_win_max: Maximum window size used by the server.
_s_win_min: Minimum window size used by the server.
_s_win_scl: Indicates whether the server uses window scaling.
_tls_session_stat: Status of the TLS (Transport Layer Security) session between the client and the server.
c_ip: IP address of the client.
time: Timestamp of the flow.
label: domain name.