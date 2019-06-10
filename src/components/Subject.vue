<template>
<div >
    <h2>Subject List</h2>
    <div style="float:right;">
    <button type="button" class="btn btn-danger" style="padding:5px;margin:5px;">Add Subject</button>
    <button type="button" class="btn btn-success" style="padding:5px;margin:5px;">Remove Subject</button>
    </div>
        <table class="table table-bordered">
            <thead class="thead-dark">
                <tr>
                <th scope="col">#</th>
                <th scope="col">Subject ID</th>
                <th scope="col">Subject Name</th>
                <th scope="col">Class</th>
                <th scope="col">Board</th>
                <th scope="col">Actions</th>

                </tr>
            </thead>
        <tbody>
                <tr>
                <th scope="row">1</th>
                <td>Maths106</td>
                <td>Maths</td>
                <td>10</td>
                <td>CBSE</td>
                <td><button class="btn btn-success">Edit</button></td>
                </tr>

                <tr>
                <th scope="row">2</th>
                <td>Science1120</td>
                <td>Science</td>
                <td>11</td>
                <td>ICSE</td>
                <td><button class="btn btn-success">Edit</button></td>
                </tr>

                <tr>
                <th scope="row">3</th>
                <td>Chemistry7843</td>
                <td>Chemistry</td>
                <td>12</td>
                <td>HSC</td>
                <td><button class="btn btn-success">Edit</button></td>
                </tr>
        </tbody>
</table>

</div>
</template>
