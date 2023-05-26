---
title: "Riboswitch - Riboswitch"
layout: riboswitch
excerpt: "Riboswitch - Riboswitch"
sitemap: false
permalink: /riboswitches/
---
# Ribozyme


<strong>The well-established natural ribozymes are the hammerhead, hairpin, hepatitis delta virus (HDV), Varkud Satellite (VS), GlmS, twister, twister sister, pistol and hatchet ribozyme, which make up the category of small ribozymes, as well as the group I and II introns, the ribosome, spliceosome and RNase P, which are classified as large ribozymes (Discovery years means the year which corresponding ribozyme was found to be certified as a ribozyme.)</strong><br><br>


> List of ribozymes 

The small ribozymes also called nucleolytic ribozymes, which are a group of relatively small RNA species (the length is distributed around 50-150 nucleotides) that catalyze site‐specific cleavage reactions. In some ribozymes, the reverse reaction (ligation) can occur. <font>

<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>Sort table example</title>
    <style>
	    body {
			font-size: 14px;
			margin: 50px 30px;
            padding-top: 10px;
      }
		  table {
        border: 2px solid #f8f8ff;
        border: 2px solid #767676;
		    border: 2px solid #767676;
		    border-radius: 5px;
		    background-color: #fff;
        }
		  th {
        background-color: #719B71;
        background-color: #719B71;
        background-color: #005826;
        color: rgba(255,255,255,0.9);
		    cursor: pointer;
        }
		  td {
		    background-color: #ffffff;
		    background-color: #f9f9f9;
		    background-color: #f9f9f9;
		    }		
		  th, td {
		  min-width: 90px;
		  padding: 10px 10px;
		}		/*
		  .arrow {
		  display: inline-block;
		  vertical-align: middle;
		  width: 0;
		  height: 0;
		  margin-left: 5px;
		  opacity: 0.66;
		}		
		  .arrow.asc {
		  border-left: 4px solid transparent;
		  border-right: 4px solid transparent;
		  border-bottom: 4px solid #fff;
		} 
		  .arrow.dsc {
		  border-left: 4px solid transparent;
		  border-right: 4px solid transparent;
		  border-top: 4px solid #fff;
		}*/
	  </style>
  </head>
    <body>
        <table id="table_id" class="table table-striped table-bordered" cellspacing="0" width="100%">
            <tr>
                <th id="th0" onclick="SortTable(this)" class="as">Name<span class="arrow asc"></span></th>
                <th id="th1" onclick="SortTable(this)" class="as">Ligand<span class="arrow asc"></span></th>
                <th id="th2" onclick="SortTable(this)" class="as">Description<span class="arrow asc"></span></th>
                <th id="th3" onclick="SortTable(this)" class="as">Discovery<span class="arrow asc"></span></th>
                <th id="th4" onclick="SortTable(this)" class="as">Rfam-name<span class="arrow asc"></span></th>
                <th id="th5" onclick="SortTable(this)" class="as">Rfam-ID<span class="arrow asc"></span></th>
            </tr>
            <tr>
                <td colspan="6"><font size=4> Ligand classification</font></td>
            </tr>
            <tr>
                <td name="td0"><a href="https://www.ribocentre.org/docs/HMP-PP" target="_blank"><b>HMP-PP</b></a></td>
                <td name="td1">ligand name.</td>
                <td name="td2">简单描述内容.</td>
                <td name="td3"><a href="https://www.ncbi.nlm.nih.gov/pubmed/17833317" target="_blank"><b>时间</b> </a></td>
                <td name="td4">NA<br></td>
                <td name="td5">NA</td>
            </tr>
            <tr>
                <td name="td0"><a href="https://www.ribocentre.org/docs/xpt-pbuX" target="_blank"><b>xpt-pbuX</b></a></td>
                <td name="td1">ligand name.</td>
                <td name="td2">简单描述内容.</td>
                <td name="td3"><a href="https://www.ncbi.nlm.nih.gov/pubmed/17833317" target="_blank"><b>时间</b> </a></td>
                <td name="td4">
                Purine riboswitch<br>
                </td>
                <td name="td5"><a href="https://rfam.xfam.org/family/RF00167" target="_blank"><b>RF00167</b></a></td>
            </tr>
            <tr>
                <td name="td0"><a href="https://www.ribocentre.org/docs/THF" target="_blank"><b>THF</b></a></td>
                <td name="td1">ligand name.</td>
                <td name="td2">简单描述内容.</td>
                <td name="td3"><a href="https://www.ncbi.nlm.nih.gov/pubmed/17833317" target="_blank"><b>时间</b> </a></td>
                <td name="td4">
                ?????<br>
                </td>
                <td name="td5"><a href="https://rfam.xfam.org/family/F01831" target="_blank"><b>F01831</b></a></td>
            </tr>
            <tr>
                <td colspan="6"><font size=4> Ligand classification</font></td>
            </tr>
            <tr>
                <td name="td0"><a href="https://www.ribocentre.org/docs/groupI.html" target="_blank"><b>Group I self-splicing intron</b></a></td>
                <td name="td1">1111</td>
                <td name="td2">1111</td>
                <td name="td3"><a href="https://www.ncbi.nlm.nih.gov/pubmed/6297745" target="_blank"><b>1982</b></a></td>
                <td name="td4">Group I catalytic intron</td>
                <td name="td5"><a href="https://rfam.xfam.org/family/RF01807" target="_blank"><b>RF00028</b></a></td>
           </tr>
        </table>
    </body>
</html><br><br>
  
<!--<script type="text/javascript"> 
    var tag=1;
    function SortTable(obj){
        var td0s=document.getElementsByName("td0");//得到id为td0的一串列表，下相同
        var td1s=document.getElementsByName("td1");
        var td2s=document.getElementsByName("td2");
        var td3s=document.getElementsByName("td3");
        var td4s=document.getElementsByName("td4");
        var tdArray0=[];
        var tdArray1=[];
        var tdArray2=[];
        var tdArray3=[];
        var tdArray4=[];
        for(var i=0;i<td0s.length;i++){
            tdArray0.push(td0s[i].innerHTML);
        }//每串都写到数组中
        for(var i=0;i<td1s.length;i++){
            tdArray1.push(td1s[i].innerHTML);
        }
        for(var i=0;i<td2s.length;i++){
            tdArray2.push(td2s[i].innerHTML);
        }
        for(var i=0;i<td3s.length;i++){
            tdArray3.push(td3s[i].innerHTML);
        }
        for(var i=0;i<td4s.length;i++){
            tdArray4.push(td4s[i].innerHTML);
        }
        var tds = document.getElementsByName("td" + obj.id.substr(2, 1));
        //得到当前传入对象的那一列
        var columnArray=[];
        for(var i=0;i<tds.length;i++){
            columnArray.push(tds[i].innerHTML);
        }//当前那一列都写入column这个栈，是逆序的
        var orginArray=[];
        for(var i=0;i<columnArray.length;i++){
            orginArray.push(columnArray[i]);
        }//将这一列的内容再存储一遍，一会原来列表修改以后，
        //通过比对值的方式对应到当前行的内容，实现同行内容一起修改
        columnArray.sort();   //排序后的新值，只排序了当前列
        for(var i=0;i<columnArray.length;i++){
            for(var j=0;j<orginArray.length;j++){
                if(orginArray[j]==columnArray[i]){
                    document.getElementsByName("td0")[i].innerHTML=tdArray0[j];
                    document.getElementsByName("td1")[i].innerHTML=tdArray1[j];
                    document.getElementsByName("td2")[i].innerHTML=tdArray2[j];
                    document.getElementsByName("td3")[i].innerHTML=tdArray3[j];
                    document.getElementsByName("td4")[i].innerHTML=tdArray4[j];
                    orginArray[j]=null;
                    break;
                }
            }
        }
    }
</script>-->



