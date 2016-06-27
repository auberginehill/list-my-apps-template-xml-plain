## List My Apps Template - XML plain

<table>
   <tr>
        <td><strong>OS:</strong></td>
        <td>Android</td>
   </tr>
   <tr>
        <td><strong>Type:</strong></td>
        <td>A template for an Android app called '<a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a>'</td>
   </tr>
   <tr>
        <td><strong>Language:</strong></td>
        <td>XML (with custom variables)</td>
   </tr>
   <tr>
        <td><strong>Description:</th>
        <td>This template (when run in an Android app called 'List My Apps') creates a .xml-file of the apps installed on an Android device. The resulted XML-file can be imported into Microsoft Excel (as described in the Tutorial Step 12 below). The Import to Excel -procedure automagically arranges the data into a column style format based on the headers, makes the columns sortable with a click and applies some styling to the data.</td>
   </tr>
   <tr>
        <td><strong>Homepage:</strong></td>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain">https://github.com/auberginehill/list-my-apps-template-xml-plain</a></td>
   </tr>
   <tr>
        <td><strong>Version:</strong></td>
        <td>1.1</td>
   </tr>
   <tr>
        <td><strong>Sources:</strong></td>
        <td>
            <table>
                <tr>
                    <td>Emojis:</td>
                    <td><a href="https://api.github.com/emojis">https://api.github.com/emojis</a></td>
                </tr>
                <tr>
                    <td>Descriptions of the variables:</td>
                    <td><a href="http://www.onyxbits.de/faq-page/22#t22n48">http://www.onyxbits.de/faq-page/22#t22n48</a></td>
                </tr>
            </table>
        </td>
   </tr>
   <tr>
        <td><strong>Download:</strong></td>
        <td>For instance <a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/all_in_one.txt">all_in_one.txt</a> or the same file in <a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/file_header.txt">three</a> <a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/body.txt">separate</a> <a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/file_footer.txt">parts</a>.</td>
   </tr>
</table>



#### Screenshot

<img class="screenshot" title="screenshot" alt="screenshot" height="100%" width="100%" align="absmiddle" src="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/example.png">



#### Remarks

<table>
   <tr>
        <th><img class="emoji" title="remarks" alt="remarks" height="28" width="28" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/26a0.png"></th>
        <td>
            <ul>
                <li>List My Apps custom templates consist of three fields ("List header", "Item format" and "List footer"). The template code in this project is divided into three parts, which correspond the fields found in List My Apps' Template Editor as described below:</li>
            </ul>
        </td>
   </tr>
   <tr>
        <td></td>
        <td>
            <ul>
                <ol>
                    <table>
                        <tr>
                            <td><strong>Filename</strong></td>
                            <td><strong>Field in List My Apps' Template Editor</strong></td>
                        </tr>
                        <tr>
                            <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/file_header.txt">file_header.txt</a></td>
                            <td>"List header, may be blank"</td>
                        </tr>
                        <tr>
                            <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/body.txt">body.txt</a></td>
                            <td>"Item format, may not be blank"</td>
                        </tr>
                        <tr>
                            <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/file_footer.txt">file_footer.txt</a></td>
                            <td>"List footer, may be blank"</td>
                        </tr>
                        <tr>
                            <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/all_in_one.txt">all_in_one.txt</a></td>
                            <td>Contains all the above mentioned three parts in one file.</td>
                        </tr>
                    </table>
                </ol>
                <li>Please include one empty row after "File Header" and "Body" in the List My Apps template (so that the script will write each data row on its own row).</li>
                <li>After the app data has been pasted from 'List My Apps' to a XML-editor, please search for the character <code>&</code> and replace every occurence with the word and (since XML-files don't work that well with extra ampersands or with extra &lt; characters).</li>
                <li>The resulted XML-file needs to be further processed in order to create a human readable file (Tutorial Step 12).</li>
            </ul>
        </td>
   </tr>
</table>



#### Tutorial

<table>
   <tr>
        <th><img class="emoji" title="tutorial" alt="tutorial" height="28" width="28" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4d6.png"></th>
        <td>To open this code with an Android device, for instance:</td>
   </tr>
   <tr>
        <td></td>
        <td>
            <ol>
                <p>
                    <li>Create a new template in '<a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a>' -app's Template Editor by clicking Options (three dots) → Template Editor → Add. [<a href="http://groovyandroid.com/wp-content/uploads/2013/10/List-My-Apps-select-all.png">Screenshot</a>]</li>
                </p>
                <p>
                    <li>Type in a name for the template.<br><br>
                       <ol>
                          <img class="screenshot" title="screenshot" alt="screenshot" height="70%" width="70%" align="absmiddle" src="https://raw.githubusercontent.com/auberginehill/list-my-apps-template-table/master/list_my_apps_-_template_editor.png">
                       </ol>
                    </li>
                </p>
                <p>
                    <li>Paste all the appropriate template data (the three sections as specified below) to 'List My Apps'. Please include one empty row after "File Header" and "Body" (so that the script will write each data row on its own row) and save the template.
                        <ol>
                            <table>
                                <tr>
                                    <td><strong>Filename</strong></td>
                                    <td><strong>Field in List My Apps' Template Editor</strong></td>
                                </tr>
                                <tr>
                                    <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/file_header.txt">file_header.txt</a></td>
                                    <td>"List header, may be blank"</td>
                                </tr>
                                <tr>
                                    <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/body.txt">body.txt</a></td>
                                    <td>"Item format, may not be blank"</td>
                                </tr>
                                <tr>
                                    <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/file_footer.txt">file_footer.txt</a></td>
                                    <td>"List footer, may be blank"</td>
                                </tr>
                                <tr>
                                    <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/blob/master/all_in_one.txt">all_in_one.txt</a></td>
                                    <td>Contains all the above mentioned three parts in one file.</td>
                                </tr>
                            </table>
                        </ol>
                    </li>
                </p>
                <p>
                    <li>Go back to the 'List My Apps' -app's home screen and select the name that was created in Step 2 from the 'Copy/Share as:' -dropdown menu. Please also select the apps that you'd like to be included in the list. [<a href="http://groovyandroid.com/wp-content/uploads/2013/10/List-My-App-HTML-list.png">Screenshot</a>]</li>
                </p>
                <p>
                    <li>'Run' the 'List My Apps' -app with the new template by copying the app data to Clipboard [Copy] (since direct sharing may not work, if a lot of applications has been installed).
                        <ul>
                            <li>There seems to be some kind of a limit, how much data the Android Clipboard can contain. With verbose templates ~200 apps might be the upper limit, but with a simple template, the Android Clipboard clearly is capable of containing considerably more app data.</li>
                        </ul>
                    </li>
                </p>
                <p>
                    <li>Open a XML-editor, such as <a href="https://play.google.com/store/apps/details?id=com.aor.droidedit">DroidEdit Free</a>.</li>
                </p>
                <p>
                    <li>Paste the app data (source code generated by 'List My Apps' in Step 5) from Clipboard to the XML-editor.
                        <ul>
                            <li>If nothing happens (no data is pasted to a XML-editor after a few seconds), try selecting fewer apps in 'List My Apps' and go back to Step 5.</li>
                                <ul>
                                    <li>Depending on the device some lagging may occur when trying to paste, say ~10000 lines of code.</li>
                                </ul>
                            <li>If "old data" gets pasted to a XML-editor (i.e. "the data that was in the Clipboard before List My Apps' 'Copy to Clipboard' -button was clicked"), try selecting fewer apps in 'List My Apps' and go back to Step 5.</li>
                        </ul>
                    </li>
                </p>
                <p>
                    <li>After pasting the app data to the XML-editor, please search for the character <code>&</code> and replace every occurence with the word and (since XML-files don't work that well with extra ampersands or with extra &lt; characters).</li>
                </p>
                <p>
                    <li>Save the file as a .xml-file, for example as 'Installed_Apps.xml', for example in 'Home/Documents' folder (a filename without any spaces is recommended).</li>
                </p>
                <p>
                    <li><a href="https://play.google.com/store/apps/details?id=org.mozilla.firefox">Firefox for Android</a> renders also .xml-files, but since the plain XML-format is quite unlegible without any styling applied, one might want to open it in Excel instead. So...</li>
                </p>                             
                <p>
                    <li>Copy the .xml-file to, for instance, <code>C:\Temp\</code> -directory in Windows.</li>
                </p>
                <p>
                    <li><strong>Microsoft Excel</strong>
                        <ul>
                            <li>On the Data tab of the Ribbon bar, in the Get External Data group, click From Another Source and choose XML. Then, in the Import Data dialog box, double-click the Installed_Apps.xml file.</li>
                            <li>Click OK on the error message.</li>
                            <li>Select where the imported cells are placed and click OK.</li>
                            <ul>
                                <li>Alternative solution: <a href="https://algconsultings.wordpress.com/2010/10/24/import-data-into-excel-xml/">Import Data Into Excel – XML</a></li>
                            </ul>
                        </ul>
                    </li>
                </p>
            </ol>
        </td>
   </tr>
</table>



#### Contributing

<p>Find a bug? Have a feature request? Here is how you can contribute to this project:</p>

 <table>
   <tr>
      <th><img class="emoji" title="contributing" alt="contributing" height="28" width="28" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f33f.png"></th>
      <td><strong>Bugs:</strong></td>
      <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/issues">Submit bugs</a> and help us verify fixes.</td>
   </tr> 
   <tr>
      <td rowspan="2"></td>
      <td><strong>Feature Requests:</strong></td>
      <td>Feature request can be submitted by <a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/issues">creating an Issue</a>.</td>
   </tr> 
   <tr>
      <td><strong>Edit Source Files:</strong></td>
      <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain/pulls">Submit pull requests</a> for bug fixes and features and discuss existing proposals.</td>
   </tr>
 </table>   



#### www

<table>
   <tr>
        <th><img class="emoji" title="www" alt="www" height="28" width="28" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f310.png"></th>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain">Template Homepage</a></td>
   </tr>
   <tr>
        <td rowspan="8"></td>
        <td><a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a> (Google Play)</td>
   </tr>
   <tr>
        <td><a href="http://www.onyxbits.de/listmyapps">List My Apps' homepage</a></td>
   </tr>
   <tr>
        <td><a href="http://forum.xda-developers.com/showthread.php?t=2460266">List My Apps' application thread</a> at xda-developers.com</td>
   </tr> 
   <tr>
      <td><a href="https://play.google.com/store/apps/details?id=com.aor.droidedit">DroidEdit Free</a> (free code editor)</td>
   </tr>
   <tr>
      <td><a href="https://play.google.com/store/apps/details?id=fr.xgouchet.xmleditor">Axel (XML Editor / Viewer)</a></td>
   </tr>
   <tr>
      <td><a href="https://play.google.com/store/apps/details?id=org.mozilla.firefox">Firefox for Android</a></td>
   </tr>
   <tr>
      <td><a href="https://text-compare.com/#">Text Compare</a></td>
   </tr>
   <tr>
      <td><a href="http://htmlescape.net/htmlescape_tool.html">Escape HTML Entities</a></td>
   </tr>
</table>



#### Related scripts

 <table>
   <tr>
        <th><img class="emoji" title="www" alt="www" height="28" width="28" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/0023-20e3.png"></th>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-table">List My Apps Template - Table</a></td>
   </tr>
   <tr>
        <td rowspan="5"></td>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-list">List My Apps Template - List</a></td>
   </tr>
   <tr>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-pro">List My Apps Template - Pro</a></td>
   </tr>
   <tr>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-data">List My Apps Template - Data</a></td>
   </tr>
   <tr>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-style">List My Apps Template - XML style</a></td>
   </tr>
   <tr>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-json">List My Apps Template - JSON</a></td>
   </tr>
</table>  



#### N.B.

<table>
    <tr>
        <th><img class="emoji" title="www" alt="www" height="28" width="28" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/2757.png"></th>
        <td>
            <ul>
                <li>Please include one empty row after "File Header" and "Body" in the List My Apps template (so that the script will write each data row on its own row).</li>
            </ul>
        </td>
    </tr>
    <tr>
        <td></td>
        <td>
            <ul>
                <li>After the app data has been pasted from 'List My Apps' to a XML-editor, please search for the character <code>&</code> and replace every occurence with the word and (since XML-files don't work that well with extra ampersands or with extra &lt; characters).</li>
            </ul>
        </td>
    </tr>
</table>
