<h1>Get LBA From Drive Capacity</h1>
<p>If you need to calculate the number of LBAs for a given drive capacity, here's the calculator for you. Just enter the drive capacity in GB below, and see the result in LBAs. If your capacity is written in TB, 1TB is 1000GB, 2TB is 2000GB etc.</p> 

<p>Enter Drive capacity in GB: <input oninput="myCalcFromGiga()" type="number" name="gbytes" id="gbytes" /></p>

<input type="text" name="lba" id="lba" readonly />

<aside>
<h2>Why would you need this&#63;</h2>
<p>Maybe you&apos;re attempting to clone a disk without first powering it up to read the total capacity. Who knows. But if you do need it, here it is.</p>
</aside>
<aside>
<h2>What&apos;s an LBA&#63;</h2>
<p>LBAs are Logical Block Addresses. When you access a disk through normal means, the first sector / block will be LBA 0. Behind the scenes, the disk controller can store that wherever it chooses. That would be the physical block address / PBA.</p>
