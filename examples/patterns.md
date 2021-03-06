# Translation Patterns
            

            
- Green: implemented
- Yellow: partly implemented
- Pink: not yet implemented

## Inhibition

### By Binding
<table style="background: #FF9E91">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/inhibition/by_binding/pd.png" height="210"/>
			<br />
			<a href="../examples/inhibition/by_binding/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/inhibition/by_binding/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/inhibition/by_binding/af.png" height="210"/>
			<br />
			<a href="../examples/inhibition/by_binding/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/inhibition/by_binding/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">A binds B to a complex, reducing concentration of B and stimulation of reaction D1 to D2, hence inhibiting the reaction D1 to D2</td>
	</tr>
</table>

### By Modification
<table style="background: #FF9E91">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/inhibition/by_modification/pd.png" height="210"/>
			<br />
			<a href="../examples/inhibition/by_modification/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/inhibition/by_modification/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/inhibition/by_modification/af.png" height="210"/>
			<br />
			<a href="../examples/inhibition/by_modification/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/inhibition/by_modification/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">A stimulates B1 to become B2, reducing concentration of B1 and stimulation of reaction C1 to C2, hence inhibiting the reaction C1 to C2</td>
	</tr>
</table>


## Simple Control

### Simple Negative Control
<table style="background: #FFF3BB">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/simple_control/simple_negative_control/pd.png" height="210"/>
			<br />
			<a href="../examples/simple_control/simple_negative_control/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/simple_control/simple_negative_control/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/simple_control/simple_negative_control/af.png" height="210"/>
			<br />
			<a href="../examples/simple_control/simple_negative_control/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/simple_control/simple_negative_control/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">A inhibits a reaction of modification B to C, while B participates also in some other reaction</td>
	</tr>
</table>

### Simple Positive Control
<table style="background: #FFF3BB">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/simple_control/simple_positive_control/pd.png" height="210"/>
			<br />
			<a href="../examples/simple_control/simple_positive_control/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/simple_control/simple_positive_control/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/simple_control/simple_positive_control/af.png" height="210"/>
			<br />
			<a href="../examples/simple_control/simple_positive_control/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/simple_control/simple_positive_control/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">A controls a reaction of modification B to C, while B also participates in some other reeactions</td>
	</tr>
</table>

### Simple Negative Control With Dead End
<table style="background: #C2FFBB">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/simple_control/simple_negative_control_with_dead_end/pd.png" height="210"/>
			<br />
			<a href="../examples/simple_control/simple_negative_control_with_dead_end/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/simple_control/simple_negative_control_with_dead_end/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/simple_control/simple_negative_control_with_dead_end/af.png" height="210"/>
			<br />
			<a href="../examples/simple_control/simple_negative_control_with_dead_end/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/simple_control/simple_negative_control_with_dead_end/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">A inhibits a reaction of modification B to C, while B participates only in this reaction</td>
	</tr>
</table>

### Simple Positive Control With Dead End
<table style="background: #C2FFBB">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/simple_control/simple_positive_control_with_dead_end/pd.png" height="210"/>
			<br />
			<a href="../examples/simple_control/simple_positive_control_with_dead_end/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/simple_control/simple_positive_control_with_dead_end/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/simple_control/simple_positive_control_with_dead_end/af.png" height="210"/>
			<br />
			<a href="../examples/simple_control/simple_positive_control_with_dead_end/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/simple_control/simple_positive_control_with_dead_end/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">A stimulates a reaction of modification B to C, while B participates only in this reaction</td>
	</tr>
</table>


## Translation Pattern

### Self Stimulation
<table style="background: #C2FFBB">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/translation_pattern/self_stimulation/pd.png" height="210"/>
			<br />
			<a href="../examples/translation_pattern/self_stimulation/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/translation_pattern/self_stimulation/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/translation_pattern/self_stimulation/af.png" height="210"/>
			<br />
			<a href="../examples/translation_pattern/self_stimulation/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/translation_pattern/self_stimulation/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">If some element controls reaction it also takes part as a substrate (self-stimulation or self-inhibition), then this control is not translated into a self-influence on AF diagram</td>
	</tr>
</table>

### Collapsing Equal Name Elements
<table style="background: #C2FFBB">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/translation_pattern/collapsing_equal_name_elements/pd.png" height="210"/>
			<br />
			<a href="../examples/translation_pattern/collapsing_equal_name_elements/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/translation_pattern/collapsing_equal_name_elements/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/translation_pattern/collapsing_equal_name_elements/af.png" height="210"/>
			<br />
			<a href="../examples/translation_pattern/collapsing_equal_name_elements/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/translation_pattern/collapsing_equal_name_elements/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">If several PD elements have the same name, then translation collapses them into a single AF element with this name. Elements considered to be of the same name, if they have equal labels, even if their states are different. All influences on reactions these elements possesed are joined into the single new one.</td>
	</tr>
</table>

### Process Is A Positive Influence
<table style="background: #C2FFBB">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/translation_pattern/process_is_a_positive_influence/pd.png" height="210"/>
			<br />
			<a href="../examples/translation_pattern/process_is_a_positive_influence/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/translation_pattern/process_is_a_positive_influence/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/translation_pattern/process_is_a_positive_influence/af.png" height="210"/>
			<br />
			<a href="../examples/translation_pattern/process_is_a_positive_influence/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/translation_pattern/process_is_a_positive_influence/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">Plain process without enzyme regulation is translated as a positive-influence</td>
	</tr>
</table>


## Source-And-Sinks

### Control Over Sink
<table style="background: #C2FFBB">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/source-and-sinks/control_over_sink/pd.png" height="210"/>
			<br />
			<a href="../examples/source-and-sinks/control_over_sink/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/source-and-sinks/control_over_sink/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/source-and-sinks/control_over_sink/af.png" height="210"/>
			<br />
			<a href="../examples/source-and-sinks/control_over_sink/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/source-and-sinks/control_over_sink/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">A sink takes role of outcoming metabolite in the simple control pattern, it should not be represented in Activity Flow diagram. B is included to AF diagram, even if it participates only in this reaction</td>
	</tr>
</table>

### Control Over Source
<table style="background: #C2FFBB">
	<tr style="font-size:90%;">
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/source-and-sinks/control_over_source/pd.png" height="210"/>
			<br />
			<a href="../examples/source-and-sinks/control_over_source/pd.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/source-and-sinks/control_over_source/pd.sbgn" target="_blank">Newt</a>
		</td>
		<td style="text-align:center; font-size:90%;">
			<img src="../examples/source-and-sinks/control_over_source/af.png" height="210"/>
			<br />
			<a href="../examples/source-and-sinks/control_over_source/af.sbgn">SBGN-ML</a>&ensp;			<a href="http://web.newteditor.org/?URL=http://sbgnbricks.github.io/examples/source-and-sinks/control_over_source/af.sbgn" target="_blank">Newt</a>
		</td>
	</tr>
	<tr style="line-height: 3em">
		<td colspan="2" style="text-align:center; font-size:90%;">A source takes role of incoming metabolite in the simple control pattern, it should not be represented in Activity Flow diagram. In contrary to the source, C element is always included into AF diagram, even if it doesn't participate in other reactions</td>
	</tr>
</table>

