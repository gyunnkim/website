
### Synopsis


Output a kubeconfig file for an additional user.


```
kubeadm kubeconfig user [flags]
```

### Examples

```
  # Output a kubeconfig file for an additional user named foo using a kubeadm config file bar
  kubeadm kubeconfig user --client-name=foo --config=bar
```

### Options

   <table style="width: 100%; table-layout: fixed;">
<colgroup>
<col span="1" style="width: 10px;" />
<col span="1" />
</colgroup>
<tbody>

<tr>
<td colspan="2">--client-name string</td>
</tr>
<tr>
<td></td><td style="line-height: 130%; word-wrap: break-word;">The name of user. It will be used as the CN if client certificates are created</td>
</tr>

<tr>
<td colspan="2">--config string</td>
</tr>
<tr>
<td></td><td style="line-height: 130%; word-wrap: break-word;">Path to a kubeadm configuration file.</td>
</tr>

<tr>
<td colspan="2">-h, --help</td>
</tr>
<tr>
<td></td><td style="line-height: 130%; word-wrap: break-word;">help for user</td>
</tr>

<tr>
<td colspan="2">--org stringSlice</td>
</tr>
<tr>
<td></td><td style="line-height: 130%; word-wrap: break-word;">The orgnizations of the client certificate. It will be used as the O if client certificates are created</td>
</tr>

<tr>
<td colspan="2">--token string</td>
</tr>
<tr>
<td></td><td style="line-height: 130%; word-wrap: break-word;">The token that should be used as the authentication mechanism for this kubeconfig, instead of client certificates</td>
</tr>

</tbody>
</table>



### Options inherited from parent commands

   <table style="width: 100%; table-layout: fixed;">
<colgroup>
<col span="1" style="width: 10px;" />
<col span="1" />
</colgroup>
<tbody>

<tr>
<td colspan="2">--rootfs string</td>
</tr>
<tr>
<td></td><td style="line-height: 130%; word-wrap: break-word;">[EXPERIMENTAL] The path to the 'real' host root filesystem.</td>
</tr>

</tbody>
</table>



