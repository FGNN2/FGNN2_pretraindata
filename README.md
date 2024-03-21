# Dataset
This repo contains circuit functionality learning dataset download instructions and documentation.

This dataset is made from open-source logic synthesis tool [ABC](https://github.com/berkeley-abc/abc) and [Yosys](https://github.com/YosysHQ/yosys), together with our customized rewriting algorithm.

Following is a table that illustrates the number of samples contained in the dataset:

<table>
    <tr>
        <td rowspan="2">Input Width</td>
        <td colspan="5",style=”text-align: center;”>Replacement Ratio</td>
    </tr>
    <tr>
        <td>10%</td>
        <td>20%</td>
        <td>30%</td>
        <td>50%</td>
        <td>total</td>
    </tr>
    <tr>
        <td>4</td>
        <td>5666</td>
        <td>5548</td>
        <td>4302</td>
        <td>3924</td>
        <td>19440</td>
    </tr>
    <tr>
        <td>5</td>
        <td>200000</td>
        <td>200000</td>
        <td>200000</td>
        <td>200000</td>
        <td>800000</td>
    </tr>
    <tr>
        <td>6</td>
        <td>200000</td>
        <td>200000</td>
        <td>200000</td>
        <td>200000</td>
        <td>800000</td>
    </tr>
    <tr>
        <td>7</td>
        <td>200000</td>
        <td>200000</td>
        <td>200000</td>
        <td>200000</td>
        <td>800000</td>
    </tr>
    <tr>
        <td>total</td>
        <td>605666</td>
        <td>605548</td>
        <td>604302</td>
        <td>603924</td>
        <td>2419440</td>
    </tr>
</table>

## Raw AIG Download

You can now download our raw AIG data from the following link: (7-zipped ~3GB)

https://drive.google.com/file/d/1thF6OO6mk4q7v5iGvUx2ISuGQsaMNTnq/view?usp=share_link

The archive contains:

* The netlists of a large number of synthetic truth table circuits in the AIG format (.bench) with the input width ranges from 4 to 7.
* The augmented positive pairs of each truth table netlist using replacement ratios 10%, 20%, 40%, and 50%. Note that the augmentation changes the topology while maintaining the Boolean functionality.


## Graph Data Download for GNN Training & Inference
Please use the link below. The 7-zipped file is about  2.5GB in size.

https://drive.google.com/file/d/1Ta8uUgVYzAW5fvQExN3RXRmYlX703rXC/view?usp=share_link

## Documentation
You can also refer to our [code](https://github.com/ZeayW/FGNN2) for usage.



