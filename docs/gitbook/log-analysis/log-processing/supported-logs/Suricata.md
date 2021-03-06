
<!-- This document is generated by "mage doc:logs". DO NOT EDIT! -->
# Suricata
{% hint style="info" %}Required fields are in <b>bold</b>.{% endhint %}
##Suricata.Anomaly
Suricata parser for the Anomaly event type in the EVE JSON output.
Reference: https://suricata.readthedocs.io/en/suricata-5.0.2/output/eve/eve-json-output.html#anomaly
<table>
<tr><th align=center>Column</th><th align=center>Type</th><th align=center>Description</th></tr>
<tr><td valign=top><code><b>anomaly</b></code></td><td><code>{<br>&nbsp;&nbsp;"code":bigint,<br>&nbsp;&nbsp;"event":string,<br>&nbsp;&nbsp;"layer":string,<br>&nbsp;&nbsp;"type":string<br>}</code></td><td valign=top>Suricata Anomaly Anomaly</td></tr>
<tr><td valign=top><code>app_proto</code></td><td><code>string</code></td><td valign=top>Suricata Anomaly AppProto</td></tr>
<tr><td valign=top><code>community_id</code></td><td><code>string</code></td><td valign=top>Suricata Anomaly CommunityID</td></tr>
<tr><td valign=top><code>dest_ip</code></td><td><code>string</code></td><td valign=top>Suricata Anomaly DestIP</td></tr>
<tr><td valign=top><code>dest_port</code></td><td><code>int</code></td><td valign=top>Suricata Anomaly DestPort</td></tr>
<tr><td valign=top><code><b>event_type</b></code></td><td><code>string</code></td><td valign=top>Suricata Anomaly EventType</td></tr>
<tr><td valign=top><code>flow_id</code></td><td><code>bigint</code></td><td valign=top>Suricata Anomaly FlowID</td></tr>
<tr><td valign=top><code>icmp_code</code></td><td><code>bigint</code></td><td valign=top>Suricata Anomaly IcmpCode</td></tr>
<tr><td valign=top><code>icmp_type</code></td><td><code>bigint</code></td><td valign=top>Suricata Anomaly IcmpType</td></tr>
<tr><td valign=top><code>metadata</code></td><td><code>{<br>&nbsp;&nbsp;"flowbits":[string],<br>&nbsp;&nbsp;"flowints":{<br>&nbsp;&nbsp;&nbsp;&nbsp;"applayer.anomaly.count":bigint,<br>&nbsp;&nbsp;&nbsp;&nbsp;"http.anomaly.count":bigint,<br>&nbsp;&nbsp;&nbsp;&nbsp;"tcp.retransmission.count":bigint,<br>&nbsp;&nbsp;&nbsp;&nbsp;"tls.anomaly.count":bigint<br>}<br>}</code></td><td valign=top>Suricata Anomaly Metadata</td></tr>
<tr><td valign=top><code>packet</code></td><td><code>string</code></td><td valign=top>Suricata Anomaly Packet</td></tr>
<tr><td valign=top><code>packet_info</code></td><td><code>{<br>&nbsp;&nbsp;"linktype":bigint<br>}</code></td><td valign=top>Suricata Anomaly PacketInfo</td></tr>
<tr><td valign=top><code>pcap_cnt</code></td><td><code>bigint</code></td><td valign=top>Suricata Anomaly PcapCnt</td></tr>
<tr><td valign=top><code>pcap_filename</code></td><td><code>string</code></td><td valign=top>Suricata Anomaly PcapFilename</td></tr>
<tr><td valign=top><code>proto</code></td><td><code>bigint</code></td><td valign=top>Suricata Anomaly Proto</td></tr>
<tr><td valign=top><code>src_ip</code></td><td><code>string</code></td><td valign=top>Suricata Anomaly SrcIP</td></tr>
<tr><td valign=top><code>src_port</code></td><td><code>int</code></td><td valign=top>Suricata Anomaly SrcPort</td></tr>
<tr><td valign=top><code><b>timestamp</b></code></td><td><code>timestamp</code></td><td valign=top>Suricata Anomaly Timestamp</td></tr>
<tr><td valign=top><code>tx_id</code></td><td><code>bigint</code></td><td valign=top>Suricata Anomaly TxID</td></tr>
<tr><td valign=top><code>vlan</code></td><td><code>[bigint]</code></td><td valign=top>Suricata Anomaly Vlan</td></tr>
<tr><td valign=top><code><b>p_log_type</b></code></td><td><code>string</code></td><td valign=top>Panther added field with type of log</td></tr>
<tr><td valign=top><code><b>p_row_id</b></code></td><td><code>string</code></td><td valign=top>Panther added field with unique id (within table)</td></tr>
<tr><td valign=top><code><b>p_event_time</b></code></td><td><code>timestamp</code></td><td valign=top>Panther added standardize event time (UTC)</td></tr>
<tr><td valign=top><code><b>p_parse_time</b></code></td><td><code>timestamp</code></td><td valign=top>Panther added standardize log parse time (UTC)</td></tr>
<tr><td valign=top><code>p_any_ip_addresses</code></td><td><code>[string]</code></td><td valign=top>Panther added field with collection of ip addresses associated with the row</td></tr>
<tr><td valign=top><code>p_any_domain_names</code></td><td><code>[string]</code></td><td valign=top>Panther added field with collection of domain names associated with the row</td></tr>
<tr><td valign=top><code>p_any_sha1_hashes</code></td><td><code>[string]</code></td><td valign=top>Panther added field with collection of SHA1 hashes associated with the row</td></tr>
<tr><td valign=top><code>p_any_md5_hashes</code></td><td><code>[string]</code></td><td valign=top>Panther added field with collection of MD5 hashes associated with the row</td></tr>
<tr><td valign=top><code>p_any_sha256_hashes</code></td><td><code>[string]</code></td><td valign=top>Panther added field with collection of SHA256 hashes of any algorithm associated with the row</td></tr>
</table>

##Suricata.DNS
Suricata parser for the DNS event type in the EVE JSON output.
Reference: https://suricata.readthedocs.io/en/suricata-5.0.2/output/eve/eve-json-output.html#dns
<table>
<tr><th align=center>Column</th><th align=center>Type</th><th align=center>Description</th></tr>
<tr><td valign=top><code>community_id</code></td><td><code>string</code></td><td valign=top>Suricata DNS CommunityID</td></tr>
<tr><td valign=top><code><b>dns</b></code></td><td><code>{<br>&nbsp;&nbsp;"aa":boolean,<br>&nbsp;&nbsp;"answers":[{<br>&nbsp;&nbsp;&nbsp;&nbsp;"rdata":string,<br>&nbsp;&nbsp;&nbsp;&nbsp;"rrname":string,<br>&nbsp;&nbsp;&nbsp;&nbsp;"rrtype":string,<br>&nbsp;&nbsp;&nbsp;&nbsp;"ttl":bigint<br>}],<br>&nbsp;&nbsp;"authorities":[{<br>&nbsp;&nbsp;&nbsp;&nbsp;"rrname":string,<br>&nbsp;&nbsp;&nbsp;&nbsp;"rrtype":string,<br>&nbsp;&nbsp;&nbsp;&nbsp;"ttl":bigint<br>}],<br>&nbsp;&nbsp;"flags":string,<br>&nbsp;&nbsp;"grouped":{<br>&nbsp;&nbsp;&nbsp;&nbsp;"A":[string],<br>&nbsp;&nbsp;&nbsp;&nbsp;"AAAA":[string],<br>&nbsp;&nbsp;&nbsp;&nbsp;"CNAME":[string],<br>&nbsp;&nbsp;&nbsp;&nbsp;"MX":[string],<br>&nbsp;&nbsp;&nbsp;&nbsp;"PTR":[string],<br>&nbsp;&nbsp;&nbsp;&nbsp;"TXT":[string]<br>},<br>&nbsp;&nbsp;"id":bigint,<br>&nbsp;&nbsp;"qr":boolean,<br>&nbsp;&nbsp;"ra":boolean,<br>&nbsp;&nbsp;"rcode":string,<br>&nbsp;&nbsp;"rd":boolean,<br>&nbsp;&nbsp;"rrname":string,<br>&nbsp;&nbsp;"rdata":string,<br>&nbsp;&nbsp;"rrtype":string,<br>&nbsp;&nbsp;"ttl":bigint,<br>&nbsp;&nbsp;"tx_id":bigint,<br>&nbsp;&nbsp;"type":string,<br>&nbsp;&nbsp;"version":bigint<br>}</code></td><td valign=top>Suricata DNS DNS</td></tr>
<tr><td valign=top><code><b>dest_ip</b></code></td><td><code>string</code></td><td valign=top>Suricata DNS DestIP</td></tr>
<tr><td valign=top><code>dest_port</code></td><td><code>int</code></td><td valign=top>Suricata DNS DestPort</td></tr>
<tr><td valign=top><code><b>event_type</b></code></td><td><code>string</code></td><td valign=top>Suricata DNS EventType</td></tr>
<tr><td valign=top><code>flow_id</code></td><td><code>bigint</code></td><td valign=top>Suricata DNS FlowID</td></tr>
<tr><td valign=top><code>pcap_cnt</code></td><td><code>bigint</code></td><td valign=top>Suricata DNS PcapCnt</td></tr>
<tr><td valign=top><code>pcap_filename</code></td><td><code>string</code></td><td valign=top>Suricata DNS PcapFilename</td></tr>
<tr><td valign=top><code><b>proto</b></code></td><td><code>bigint</code></td><td valign=top>Suricata DNS Proto</td></tr>
<tr><td valign=top><code><b>src_ip</b></code></td><td><code>string</code></td><td valign=top>Suricata DNS SrcIP</td></tr>
<tr><td valign=top><code>src_port</code></td><td><code>int</code></td><td valign=top>Suricata DNS SrcPort</td></tr>
<tr><td valign=top><code><b>timestamp</b></code></td><td><code>timestamp</code></td><td valign=top>Suricata DNS Timestamp</td></tr>
<tr><td valign=top><code>vlan</code></td><td><code>[bigint]</code></td><td valign=top>Suricata DNS Vlan</td></tr>
<tr><td valign=top><code><b>p_log_type</b></code></td><td><code>string</code></td><td valign=top>Panther added field with type of log</td></tr>
<tr><td valign=top><code><b>p_row_id</b></code></td><td><code>string</code></td><td valign=top>Panther added field with unique id (within table)</td></tr>
<tr><td valign=top><code><b>p_event_time</b></code></td><td><code>timestamp</code></td><td valign=top>Panther added standardize event time (UTC)</td></tr>
<tr><td valign=top><code><b>p_parse_time</b></code></td><td><code>timestamp</code></td><td valign=top>Panther added standardize log parse time (UTC)</td></tr>
<tr><td valign=top><code>p_any_ip_addresses</code></td><td><code>[string]</code></td><td valign=top>Panther added field with collection of ip addresses associated with the row</td></tr>
<tr><td valign=top><code>p_any_domain_names</code></td><td><code>[string]</code></td><td valign=top>Panther added field with collection of domain names associated with the row</td></tr>
<tr><td valign=top><code>p_any_sha1_hashes</code></td><td><code>[string]</code></td><td valign=top>Panther added field with collection of SHA1 hashes associated with the row</td></tr>
<tr><td valign=top><code>p_any_md5_hashes</code></td><td><code>[string]</code></td><td valign=top>Panther added field with collection of MD5 hashes associated with the row</td></tr>
<tr><td valign=top><code>p_any_sha256_hashes</code></td><td><code>[string]</code></td><td valign=top>Panther added field with collection of SHA256 hashes of any algorithm associated with the row</td></tr>
</table>

