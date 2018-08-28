<div id="ContentWrapper">
    <div class="divCourseInformation">
        <label class="lblCourseTitle">BANC</label>
        <img class="imgBtn crs_1" onClick="EditCourse(this)" src="edit.png" title="edit" alt="edit" />
        <br />
        <label class="lblCourseName">Balls And Noodles Course</label>
        <br />
        <p class="lblCourseDescription">BANC is a twelve-week high-tempo course. Student time-management and work prioritization skills are pushed to extremes, replicating requirements levied on them in real-world operational environments. This dynamic course incorporates small group instruction and scenario-based, performance-oriented, and realistic field training exercises designed to train and evaluate each of the students' ability to preform in a variety of situations. In addition to training to specific tasks, students are evaluated on their operational thinking and operational judgement.</p>
        <br />
        <table class="tblCourse">
            <thead>
                <tr>
                    <th class="left">CRRS ID</th>
                    <th>Capacity</th>
                    <th>Weeks</th>
                    <th>Days</th>
                    <th>Total Days</th>
                    <th>Objective</th>
                    <th>Prerequisites</th>
                    <th>Next Steps</th>
                    <th>Deactivate</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="bold">FVR AID/22T V</td>
                    <td class="center">36</td>
                    <td class="center">11</td>
                    <td class="center">6</td>
                    <td class="center">83</td>
                    <td class="center"><img id="btn_BANC_Objective" class="imgBtn crs_1" onClick="ViewCrsObjective(this)" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img id="btn_BANC_Prerequisite" class="imgBtn crs_1" onClick="ViewCrsPrerequisites(this)" src="note.png" title="View Prerequisites" alt="View Prerequisites" /></td>
                    <td class="center"><img id="btn_BANC_NextSteps" class="imgBtn crs_1" onClick="ViewCrsNextSteps(this)" src="note.png" title="View Next Steps" alt="View Next Steps" /></td>
                    <td class="center"><img id="btn_BANC_Deativate" class="crs_1" width="18" onClick="Deactivate(this)" src="NoFalse.png" /></td>
                </tr>
            </tbody>
        </table>
        <br />
        <img class="imgBtn crs_1" onClick="AddClass(this)" src="AddClassBtn.png" title="Add New Class" alt="Add New Class" />
        <table class="tblClass">
            <thead>
                <tr>
                    <th>Edit</th>
                    <th>Class Number</th>
                    <th>Deadline</th>
                    <th>Report</th>
                    <th>Start</th>
                    <th>End</th>
                    <th>Clearance</th>
                    <th>Capacity</th>
                    <th>Weeks</th>
                    <th>Days</th>
                    <th>Total Days</th>
                    <th>Training Type</th>
                    <th>Description</th>
                    <th>Objective</th>
                    <th>Next Steps</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="center"><img class="imgBtn cls_1" onClick="EditClass(this)" src="edit.png" title="edit" alt="edit" /></td>
                    <td class="center bold">18-001</td>
                    <td class="center bold red">01 AUG 2018</td>
                    <td class="center">01 OCT 2018</td>
                    <td class="center bold">01 OCT 2018</td>
                    <td class="center bold">05 DEC 2018</td>
                    <td class="center">Secret</td>
                    <td class="center">36</td>
                    <td class="center">11</td>
                    <td class="center">6</td>
                    <td class="center">83</td>
                    <td class="center"><img id="cls_1" class="imgBtn cls_1" onClick="ViewClsTrainingType(this)" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img id="cls_1" class="imgBtn cls_1" onClick="ViewClsDescription(this)" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img id="cls_1" class="imgBtn cls_1" onClick="ViewClsObjective(this)" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img id="cls_1" class="imgBtn" onClick="ViewClsNextSteps(this)" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                </tr>
                <tr>
                    <td class="center"><img class="imgBtn cls_2" onClick="EditClass(this)" src="edit.png" title="edit" alt="edit" /></td>
                    <td class="center bold">18-001</td>
                    <td class="center bold red">01 AUG 2018</td>
                    <td class="center">01 OCT 2018</td>
                    <td class="center bold">01 OCT 2018</td>
                    <td class="center bold">05 DEC 2018</td>
                    <td class="center">Secret</td>
                    <td class="center">36</td>
                    <td class="center">11</td>
                    <td class="center">6</td>
                    <td class="center">83</td>
                    <td class="center"><img class="imgBtn cls_2" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_2" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_2" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_2" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                </tr>
                <tr>
                    <td class="center"><img class="imgBtn cls_3" onClick="EditClass(this)" src="edit.png" title="edit" alt="edit" /></td>
                    <td class="center bold">18-001</td>
                    <td class="center bold red">01 AUG 2018</td>
                    <td class="center">01 OCT 2018</td>
                    <td class="center bold">01 OCT 2018</td>
                    <td class="center bold">05 DEC 2018</td>
                    <td class="center">Secret</td>
                    <td class="center">36</td>
                    <td class="center">11</td>
                    <td class="center">6</td>
                    <td class="center">83</td>
                    <td class="center"><img class="imgBtn cls_3" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_3" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_3" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_3" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                </tr>
                <tr>
                    <td class="center"><img class="imgBtn cls_4" onClick="EditClass(this)" src="edit.png" title="edit" alt="edit" /></td>
                    <td class="center bold">18-001</td>
                    <td class="center bold red">01 AUG 2018</td>
                    <td class="center">01 OCT 2018</td>
                    <td class="center bold">01 OCT 2018</td>
                    <td class="center bold">05 DEC 2018</td>
                    <td class="center">Secret</td>
                    <td class="center">36</td>
                    <td class="center">11</td>
                    <td class="center">6</td>
                    <td class="center">83</td>
                    <td class="center"><img class="imgBtn cls_4" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_4" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_4" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_4" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                </tr>
                <tr>
                    <td class="center"><img class="imgBtn cls_5" onClick="EditClass(this)" src="edit.png" title="edit" alt="edit" /></td>
                    <td class="center bold">18-001</td>
                    <td class="center bold red">01 AUG 2018</td>
                    <td class="center">01 OCT 2018</td>
                    <td class="center bold">01 OCT 2018</td>
                    <td class="center bold">05 DEC 2018</td>
                    <td class="center">Secret</td>
                    <td class="center">36</td>
                    <td class="center">11</td>
                    <td class="center">6</td>
                    <td class="center">83</td>
                    <td class="center"><img class="imgBtn cls_5" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_5" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_5" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_5" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                </tr>
                <tr>
                    <td class="center"><img class="imgBtn cls_6" onClick="EditClass(this)" src="edit.png" title="edit" alt="edit" /></td>
                    <td class="center bold">18-001</td>
                    <td class="center bold red">01 AUG 2018</td>
                    <td class="center">01 OCT 2018</td>
                    <td class="center bold">01 OCT 2018</td>
                    <td class="center bold">05 DEC 2018</td>
                    <td class="center">Secret</td>
                    <td class="center">36</td>
                    <td class="center">11</td>
                    <td class="center">6</td>
                    <td class="center">83</td>
                    <td class="center"><img class="imgBtn cls_6" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_6" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_6" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_6" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                </tr>
                <tr>
                    <td class="center"><img class="imgBtn cls_7" onClick="EditClass(this)" src="edit.png" title="edit" alt="edit" /></td>
                    <td class="center bold">18-001</td>
                    <td class="center bold red">01 AUG 2018</td>
                    <td class="center">01 OCT 2018</td>
                    <td class="center bold">01 OCT 2018</td>
                    <td class="center bold">05 DEC 2018</td>
                    <td class="center">Secret</td>
                    <td class="center">36</td>
                    <td class="center">11</td>
                    <td class="center">6</td>
                    <td class="center">83</td>
                    <td class="center"><img class="imgBtn cls_7" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_7" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_7" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                    <td class="center"><img class="imgBtn cls_7" src="note.png" title="View Course Objective" alt="View Course Objective" /></td>
                </tr>
            </tbody>
        </table>
    </div>
</div>
