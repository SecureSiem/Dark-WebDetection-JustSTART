To Detect TOR browser exicution...

<group name="windows, sysmon, sysmon_event1, tor">
  <rule id="130001" level="12">
    <if_matched_sid>61603</if_matched_sid>
    <match>Tor Browser</match>
    <description>Tor Browser execution detected</description>
  </rule>
</group>
