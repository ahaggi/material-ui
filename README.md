# Diagonal Cut

Quido and Hugo are making a chocolate cake. The central ingredient of the cake is a large chocolate bar, lying unwrapped on the kitchen table. The bar is an M X N rectangular grid of chocolate blocks. All of the MN blocks are rectangles of identical shape and size. The chocolate bar is of top quality and the friends want to eat part of it, before the rest is used in the cake.

“OK,” says Quido, “let’s divide the whole bar into two triangular chunks by a straight diagonal cut from its upper-left corner to its lower-right corner. We will then eat all of the blocks which have been cut exactly in half, into two equal-area pieces. You will eat one half and I will eat the other half of each such block. All other blocks, that is, the blocks which are either uncut or cut into two parts of different sizes, will go directly into the cake. Of course, we will make sure the cut is perfectly precise.

Let’s see how much chocolate we get to eat!”

## Input

The input consists of two space-separated integers M and N given on a single line, (where 1 <= M, N <= 10<sup>18</sup>). The numbers M and N denote the number of blocks in one column and in one row, respectively, in the chocolate bar.

## Output

Print the number of blocks of the chocolate bar which are cut into exactly two pieces of equal area.

<table class="sample" summary="sample data">

<tbody>

<tr>

<th>Sample Input 1</th>

<th>Sample Output 1</th>

</tr>

<tr>

<td>

<pre>6 10
</pre>

</td>

<td>

<pre>2
</pre>

</td>

</tr>

</tbody>

</table>

<table class="sample" summary="sample data">

<tbody>

<tr>

<th>Sample Input 2</th>

<th>Sample Output 2</th>

</tr>

<tr>

<td>

<pre>75206452536745713 10322579177493903
</pre>

</td>

<td>

<pre>40318322589
</pre>

</td>

</tr>

</tbody>

</table>



