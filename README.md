@charset "UTF-8";
/* ---------------- TABLE OF CONTENT ----------------------
	-----------------------------------------------------------
	-----------------------------------------------------------



	0. FRAMEWORK

	1. BASE
	   1.1. BASE
	   1.2. TYPOGRAPHY

	2. COMPONENT
	   2.1. PLUGINS
	   2.2. COMMON
	   2.3. MODULES

	3. SKELETON
	   3.1. PAGE
	   3.2. HEADER
	   3.3. FOOTER


	-----------------------------------------------------------
	-----------------------------------------------------------
------------------- END TABLE OF CONTENT ------------------*/
/* I. FRAMEWORK
***********************/
@import url('https://fonts.googleapis.com/css?family=Montez');
@import url('https://fonts.googleapis.com/css?family=Tajawal:500');
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    color: #000 !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 15px;
  padding-right: 15px;
}
@media (min-width: 768px) {
  .container {
    width: 750px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 970px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1170px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 15px;
  padding-right: 15px;
}
.row {
  margin-left: -15px;
  margin-right: -15px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 15px;
  padding-right: 15px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 100%) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 100%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: right;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 100%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 20px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #dddddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #dddddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #dddddd;
}
.table .table {
  background-color: #ffffff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #dddddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #dddddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 15px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #dddddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 20px;
  font-size: 21px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -ms-box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: thin dotted;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 14px;
  line-height: 1.42857143;
  color: #555555;
}
select,
textarea,
input[type="text"],
input[type="password"],
input[type="datetime"],
input[type="datetime-local"],
input[type="date"],
input[type="month"],
input[type="time"],
input[type="week"],
input[type="number"],
input[type="email"],
input[type="url"],
input[type="search"],
input[type="tel"],
input[type="color"],
.form-control {
  display: block;
  width: 100%;
  height: 34px;
  padding: 6px 12px;
  font-size: 14px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #ffffff;
  background-image: none;
  border: 1px solid #aaaaaa;
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s 0.3s ease-out;
  -moz-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s 0.3s ease-out;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s 0.3s ease-out;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s 0.3s ease-out;
}
select:focus,
textarea:focus,
input[type="text"]:focus,
input[type="password"]:focus,
input[type="datetime"]:focus,
input[type="datetime-local"]:focus,
input[type="date"]:focus,
input[type="month"]:focus,
input[type="time"]:focus,
input[type="week"]:focus,
input[type="number"]:focus,
input[type="email"]:focus,
input[type="url"]:focus,
input[type="search"]:focus,
input[type="tel"]:focus,
input[type="color"]:focus,
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
}
select::-moz-placeholder,
textarea::-moz-placeholder,
input[type="text"]::-moz-placeholder,
input[type="password"]::-moz-placeholder,
input[type="datetime"]::-moz-placeholder,
input[type="datetime-local"]::-moz-placeholder,
input[type="date"]::-moz-placeholder,
input[type="month"]::-moz-placeholder,
input[type="time"]::-moz-placeholder,
input[type="week"]::-moz-placeholder,
input[type="number"]::-moz-placeholder,
input[type="email"]::-moz-placeholder,
input[type="url"]::-moz-placeholder,
input[type="search"]::-moz-placeholder,
input[type="tel"]::-moz-placeholder,
input[type="color"]::-moz-placeholder,
.form-control::-moz-placeholder {
  color: #999999;
  opacity: 1;
}
select:-ms-input-placeholder,
textarea:-ms-input-placeholder,
input[type="text"]:-ms-input-placeholder,
input[type="password"]:-ms-input-placeholder,
input[type="datetime"]:-ms-input-placeholder,
input[type="datetime-local"]:-ms-input-placeholder,
input[type="date"]:-ms-input-placeholder,
input[type="month"]:-ms-input-placeholder,
input[type="time"]:-ms-input-placeholder,
input[type="week"]:-ms-input-placeholder,
input[type="number"]:-ms-input-placeholder,
input[type="email"]:-ms-input-placeholder,
input[type="url"]:-ms-input-placeholder,
input[type="search"]:-ms-input-placeholder,
input[type="tel"]:-ms-input-placeholder,
input[type="color"]:-ms-input-placeholder,
.form-control:-ms-input-placeholder {
  color: #999999;
}
select::-webkit-input-placeholder,
textarea::-webkit-input-placeholder,
input[type="text"]::-webkit-input-placeholder,
input[type="password"]::-webkit-input-placeholder,
input[type="datetime"]::-webkit-input-placeholder,
input[type="datetime-local"]::-webkit-input-placeholder,
input[type="date"]::-webkit-input-placeholder,
input[type="month"]::-webkit-input-placeholder,
input[type="time"]::-webkit-input-placeholder,
input[type="week"]::-webkit-input-placeholder,
input[type="number"]::-webkit-input-placeholder,
input[type="email"]::-webkit-input-placeholder,
input[type="url"]::-webkit-input-placeholder,
input[type="search"]::-webkit-input-placeholder,
input[type="tel"]::-webkit-input-placeholder,
input[type="color"]::-webkit-input-placeholder,
.form-control::-webkit-input-placeholder {
  color: #999999;
}
select:-moz-placeholder,
textarea:-moz-placeholder,
input[type="text"]:-moz-placeholder,
input[type="password"]:-moz-placeholder,
input[type="datetime"]:-moz-placeholder,
input[type="datetime-local"]:-moz-placeholder,
input[type="date"]:-moz-placeholder,
input[type="month"]:-moz-placeholder,
input[type="time"]:-moz-placeholder,
input[type="week"]:-moz-placeholder,
input[type="number"]:-moz-placeholder,
input[type="email"]:-moz-placeholder,
input[type="url"]:-moz-placeholder,
input[type="search"]:-moz-placeholder,
input[type="tel"]:-moz-placeholder,
input[type="color"]:-moz-placeholder,
.form-control:-moz-placeholder {
  color: #999999;
}
select::-moz-placeholder,
textarea::-moz-placeholder,
input[type="text"]::-moz-placeholder,
input[type="password"]::-moz-placeholder,
input[type="datetime"]::-moz-placeholder,
input[type="datetime-local"]::-moz-placeholder,
input[type="date"]::-moz-placeholder,
input[type="month"]::-moz-placeholder,
input[type="time"]::-moz-placeholder,
input[type="week"]::-moz-placeholder,
input[type="number"]::-moz-placeholder,
input[type="email"]::-moz-placeholder,
input[type="url"]::-moz-placeholder,
input[type="search"]::-moz-placeholder,
input[type="tel"]::-moz-placeholder,
input[type="color"]::-moz-placeholder,
.form-control::-moz-placeholder {
  color: #999999;
}
select:-ms-input-placeholder,
textarea:-ms-input-placeholder,
input[type="text"]:-ms-input-placeholder,
input[type="password"]:-ms-input-placeholder,
input[type="datetime"]:-ms-input-placeholder,
input[type="datetime-local"]:-ms-input-placeholder,
input[type="date"]:-ms-input-placeholder,
input[type="month"]:-ms-input-placeholder,
input[type="time"]:-ms-input-placeholder,
input[type="week"]:-ms-input-placeholder,
input[type="number"]:-ms-input-placeholder,
input[type="email"]:-ms-input-placeholder,
input[type="url"]:-ms-input-placeholder,
input[type="search"]:-ms-input-placeholder,
input[type="tel"]:-ms-input-placeholder,
input[type="color"]:-ms-input-placeholder,
.form-control:-ms-input-placeholder {
  color: #999999;
}
select::-webkit-input-placeholder,
textarea::-webkit-input-placeholder,
input[type="text"]::-webkit-input-placeholder,
input[type="password"]::-webkit-input-placeholder,
input[type="datetime"]::-webkit-input-placeholder,
input[type="datetime-local"]::-webkit-input-placeholder,
input[type="date"]::-webkit-input-placeholder,
input[type="month"]::-webkit-input-placeholder,
input[type="time"]::-webkit-input-placeholder,
input[type="week"]::-webkit-input-placeholder,
input[type="number"]::-webkit-input-placeholder,
input[type="email"]::-webkit-input-placeholder,
input[type="url"]::-webkit-input-placeholder,
input[type="search"]::-webkit-input-placeholder,
input[type="tel"]::-webkit-input-placeholder,
input[type="color"]::-webkit-input-placeholder,
.form-control::-webkit-input-placeholder {
  color: #999999;
}
select[disabled],
textarea[disabled],
input[type="text"][disabled],
input[type="password"][disabled],
input[type="datetime"][disabled],
input[type="datetime-local"][disabled],
input[type="date"][disabled],
input[type="month"][disabled],
input[type="time"][disabled],
input[type="week"][disabled],
input[type="number"][disabled],
input[type="email"][disabled],
input[type="url"][disabled],
input[type="search"][disabled],
input[type="tel"][disabled],
input[type="color"][disabled],
.form-control[disabled],
select[readonly],
textarea[readonly],
input[type="text"][readonly],
input[type="password"][readonly],
input[type="datetime"][readonly],
input[type="datetime-local"][readonly],
input[type="date"][readonly],
input[type="month"][readonly],
input[type="time"][readonly],
input[type="week"][readonly],
input[type="number"][readonly],
input[type="email"][readonly],
input[type="url"][readonly],
input[type="search"][readonly],
input[type="tel"][readonly],
input[type="color"][readonly],
.form-control[readonly],
fieldset[disabled] select,
fieldset[disabled] textarea,
fieldset[disabled] input[type="text"],
fieldset[disabled] input[type="password"],
fieldset[disabled] input[type="datetime"],
fieldset[disabled] input[type="datetime-local"],
fieldset[disabled] input[type="date"],
fieldset[disabled] input[type="month"],
fieldset[disabled] input[type="time"],
fieldset[disabled] input[type="week"],
fieldset[disabled] input[type="number"],
fieldset[disabled] input[type="email"],
fieldset[disabled] input[type="url"],
fieldset[disabled] input[type="search"],
fieldset[disabled] input[type="tel"],
fieldset[disabled] input[type="color"],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
select[disabled],
textarea[disabled],
input[type="text"][disabled],
input[type="password"][disabled],
input[type="datetime"][disabled],
input[type="datetime-local"][disabled],
input[type="date"][disabled],
input[type="month"][disabled],
input[type="time"][disabled],
input[type="week"][disabled],
input[type="number"][disabled],
input[type="email"][disabled],
input[type="url"][disabled],
input[type="search"][disabled],
input[type="tel"][disabled],
input[type="color"][disabled],
.form-control[disabled],
fieldset[disabled] select,
fieldset[disabled] textarea,
fieldset[disabled] input[type="text"],
fieldset[disabled] input[type="password"],
fieldset[disabled] input[type="datetime"],
fieldset[disabled] input[type="datetime-local"],
fieldset[disabled] input[type="date"],
fieldset[disabled] input[type="month"],
fieldset[disabled] input[type="time"],
fieldset[disabled] input[type="week"],
fieldset[disabled] input[type="number"],
fieldset[disabled] input[type="email"],
fieldset[disabled] input[type="url"],
fieldset[disabled] input[type="search"],
fieldset[disabled] input[type="tel"],
fieldset[disabled] input[type="color"],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textareaselect,
textareatextarea,
textareainput[type="text"],
textareainput[type="password"],
textareainput[type="datetime"],
textareainput[type="datetime-local"],
textareainput[type="date"],
textareainput[type="month"],
textareainput[type="time"],
textareainput[type="week"],
textareainput[type="number"],
textareainput[type="email"],
textareainput[type="url"],
textareainput[type="search"],
textareainput[type="tel"],
textareainput[type="color"],
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 34px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 46px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 20px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 34px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 0;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 0;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 32px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 46px;
  padding: 10px 16px;
  font-size: 18px;
  line-height: 1.3333333;
  border-radius: 0;
}
select.input-lg {
  height: 46px;
  line-height: 46px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 46px;
  padding: 10px 16px;
  font-size: 18px;
  line-height: 1.3333333;
  border-radius: 0;
}
.form-group-lg select.form-control {
  height: 46px;
  line-height: 46px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 46px;
  min-height: 38px;
  padding: 11px 16px;
  font-size: 18px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 42.5px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 34px;
  height: 34px;
  line-height: 34px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 46px;
  height: 46px;
  line-height: 46px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #0567FA;
}
.has-success .form-control {
  border-color: #0567FA;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #0567FA;
  border-color: #0567FA;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #0567FA;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  -moz-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 25px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #737373;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 27px;
}
.form-horizontal .form-group {
  margin-left: -15px;
  margin-right: -15px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 15px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 14.333333px;
    font-size: 18px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
  -webkit-transition: opacity 0.15s linear 0.3s ease-out;
  -moz-transition: opacity 0.15s linear 0.3s ease-out;
  -o-transition: opacity 0.15s linear 0.3s ease-out;
  transition: opacity 0.15s linear 0.3s ease-out;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -moz-transition-duration: 0.35s;
  -webkit-transition-duration: 0.35s;
  -o-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 14px;
  text-align: left;
  background-color: #ffffff;
  border: 1px solid #cccccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 0;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  -moz-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 9px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #ffffff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 768px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 9px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #dddddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 0 0 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #dddddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #ffffff;
  border: 1px solid #dddddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 0;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #dddddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #dddddd;
    border-radius: 0 0 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #ffffff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 0;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #ffffff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 0;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #dddddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #dddddd;
    border-radius: 0 0 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #ffffff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 50px;
  margin-bottom: 20px;
  border: 1px solid transparent;
}
@media (min-width: 768px) {
  .navbar {
    border-radius: 0;
  }
}
@media (min-width: 768px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 15px;
  padding-left: 15px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 768px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 480px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: -15px;
  margin-left: -15px;
}
@media (min-width: 768px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 768px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 768px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 15px 15px;
  font-size: 18px;
  line-height: 20px;
  height: 50px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 768px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: -15px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 15px;
  padding: 9px 10px;
  margin-top: 8px;
  margin-bottom: 8px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 0;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 768px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 7.5px -15px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 20px;
}
@media (max-width: 767px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 20px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 768px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 15px;
    padding-bottom: 15px;
  }
}
.navbar-form {
  margin-left: -15px;
  margin-right: -15px;
  padding: 10px 15px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  -moz-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: 8px;
  margin-bottom: 8px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 767px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 768px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    -moz-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: 8px;
  margin-bottom: 8px;
}
.navbar-btn.btn-sm {
  margin-top: 10px;
  margin-bottom: 10px;
}
.navbar-btn.btn-xs {
  margin-top: 14px;
  margin-bottom: 14px;
}
.navbar-text {
  margin-top: 15px;
  margin-bottom: 15px;
}
@media (min-width: 768px) {
  .navbar-text {
    float: left;
    margin-left: 15px;
    margin-right: 15px;
  }
}
@media (min-width: 768px) {
  .navbar-left {
    float: left !important;
  }
  .navbar-right {
    float: right !important;
    margin-right: -15px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777777;
}
.navbar-default .navbar-nav > li > a {
  color: #777777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #cccccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #dddddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #dddddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555555;
}
@media (max-width: 767px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #cccccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777777;
}
.navbar-default .navbar-link:hover {
  color: #333333;
}
.navbar-default .btn-link {
  color: #777777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #F50A21;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #cccccc;
}
.navbar-inverse {
  background-color: #F50A21;
  border-color: #F50A21;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #ffffff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #ffffff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #ffffff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #ffffff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #ffffff;
}
@media (max-width: 767px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #ffffff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #ffffff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #ffffff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #ffffff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444444;
}
.alert {
  padding: 15px;
  margin-bottom: 20px;
  border: 1px solid transparent;
  border-radius: 0;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #0567FA;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.close {
  float: right;
  font-size: 21px;
  font-weight: bold;
  line-height: 1;
  color: #000000;
  text-shadow: 0 1px 0 #ffffff;
  -moz-opacity: 0.2;
  -khtml-opacity: 0.2;
  -webkit-opacity: 0.2;
  opacity: 0.2;
  -ms-filter: progid:DXImageTransform.Microsoft.Alpha(opacity=20);
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000000;
  text-decoration: none;
  cursor: pointer;
  -moz-opacity: 0.5;
  -khtml-opacity: 0.5;
  -webkit-opacity: 0.5;
  opacity: 0.5;
  -ms-filter: progid:DXImageTransform.Microsoft.Alpha(opacity=50);
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  transform: translate(0, -25%);
  -webkit-transform: translate(0, -25%);
  -moz-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  transform: translate(0, 0);
  -webkit-transform: translate(0, 0);
  -moz-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #ffffff;
  border: 1px solid #999999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  -moz-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000000;
}
.modal-backdrop.fade {
  -moz-opacity: 0;
  -khtml-opacity: 0;
  -webkit-opacity: 0;
  opacity: 0;
  -ms-filter: progid:DXImageTransform.Microsoft.Alpha(opacity=0);
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  -moz-opacity: 0.5;
  -khtml-opacity: 0.5;
  -webkit-opacity: 0.5;
  opacity: 0.5;
  -ms-filter: progid:DXImageTransform.Microsoft.Alpha(opacity=50);
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
  min-height: 16.42857143px;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    -moz-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 1100px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  -moz-opacity: 0;
  -khtml-opacity: 0;
  -webkit-opacity: 0;
  opacity: 0;
  -ms-filter: progid:DXImageTransform.Microsoft.Alpha(opacity=0);
  filter: alpha(opacity=0);
}
.tooltip.in {
  -moz-opacity: 0.9;
  -khtml-opacity: 0.9;
  -webkit-opacity: 0.9;
  opacity: 0.9;
  -ms-filter: progid:DXImageTransform.Microsoft.Alpha(opacity=90);
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #ffffff;
  text-align: center;
  background-color: #000000;
  border-radius: 0;
  background: #000;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 14px;
  background-color: #ffffff;
  background-clip: padding-box;
  border: 1px solid #cccccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 0;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  -moz-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 14px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: -1 -1 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #ffffff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #ffffff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #ffffff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #ffffff;
  bottom: -10px;
}
.clearfix,
.container,
.container-fluid,
.row,
.form-horizontal .form-group,
.nav,
.navbar,
.navbar-header,
.navbar-collapse,
.modal-footer {
  *zoom: 1;
}
.clearfix:before,
.clearfix:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.modal-footer:before,
.modal-footer:after {
  content: " ";
  display: table;
}
.clearfix:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.modal-footer:after {
  clear: both;
}
.clearfix:before,
.clearfix:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.modal-footer:before,
.modal-footer:after {
  content: " ";
  display: table;
}
.clearfix:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.modal-footer:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/* I. REFERENCES */
/* II. GENERAL
***********************/
/*--------------------------------------------------------------
Reset
--------------------------------------------------------------*/
html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
font,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td {
  -moz-appearance: none;
  -webkit-appearance: none;
  -webkit-border-radius: 0;
  border: 0;
  font-family: Tajawal;
  font-size: 100%;
  font-style: inherit;
  font-weight: inherit;
  margin: 0;
  outline: 0;
  padding: 0;
  vertical-align: baseline;
}
html {
  -webkit-text-size-adjust: 100%;
  /* Prevents iOS text size adjust after orientation change, without disabling user zoom */
  -ms-text-size-adjust: 100%;
  /* www.456bereastreet.com/archive/201012/controlling_text_size_in_safari_for_ios_without_disabling_user_zoom/ */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
*,
*:before,
*:after {
  /* apply a natural box layout model to all elements; see http://www.paulirish.com/2012/box-sizing-border-box-ftw/ */
  -webkit-box-sizing: border-box;
  /* Not needed for modern webkit but still used by Blackberry Browser 7.0; see http://caniuse.com/#search=box-sizing */
  -moz-box-sizing: border-box;
  /* Still needed for Firefox 28; see http://caniuse.com/#search=box-sizing */
  box-sizing: border-box;
  outline: none;
}
body {
  overflow-x: hidden;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
main,
nav,
section {
  display: block;
}
ol,
ul {
  list-style: none;
  margin: 0;
  padding: 0;
}
table {
  /* tables still need 'cellspacing="0"' in the markup */
  border-collapse: separate;
  border-spacing: 0;
}
caption,
th,
td {
  font-weight: normal;
  text-align: left;
}
blockquote:before,
blockquote:after,
q:before,
q:after {
  content: "";
}
blockquote,
q {
  quotes: "" "";
}
a:focus {
  outline: none;
}
a:hover,
a:active {
  outline: 0;
}
a img {
  border: 0;
}
/*--------------------------------------------
Initial Setup
----------------------------------------------*/
a {
  text-decoration: none;
}
input:focus,
textarea:focus {
  outline: none;
}
img,
video {
  max-width: 100%;
  vertical-align: top;
}
audio,
canvas,
video {
  display: inline;
  zoom: 1;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  margin: 0;
}
html {
  font-size: 10px;
}
body {
  font-size: 140px;
  font-size: 14rem;
  font-size: 14px;
  font-size: 1.4rem;
  color: #333;
}
body,
button,
input,
select,
textarea {
font-family: 'Tajawal', sans-serif;  line-height: 1;
}
h1,
h2,
h3,
h4,
h5,
h6 {
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  clear: both;
  line-height: 1;
  white-space: nowrap;
  -webkit-margin-before: 0;
  -webkit-margin-after: 0;
  -webkit-margin-start: 0;
  -webkit-margin-end: 0;
}
h1{
  font-size: 32px;
}
h2 {
  font-size: 28px;
}
h3 {
  font-size: 24px;
}
h4 {
  font-size: 20px;
}
h5 {
  font-size: 18px;
}
h6 {
  font-size: 16px;
}
p {
  margin: 0;
  -webkit-margin-before: 0;
  -webkit-margin-after: 0;
}
b,
strong {
  font-weight: 700;
}
dfn,
cite,
em,
i {
  font-style: italic;
}
blockquote {
  border-left: 4px solid #707070;
  border-left: 4px solid rgba(51, 51, 51, 0.7);
  color: #707070;
  color: rgba(51, 51, 51, 0.7);
  font-size: 18px;
  font-size: 1.8rem;
  font-style: italic;
  line-height: 1.6667;
  margin-bottom: 1.6667em;
  padding-left: 0.7778em;
}
blockquote p {
  margin-bottom: 1.6667em;
}
blockquote > p:last-child {
  margin-bottom: 0;
}
blockquote cite,
blockquote small {
  color: #333;
  font-size: 15px;
  font-size: 1.5rem;
  font-family: "Noto Sans", sans-serif;
  line-height: 1.6;
}
blockquote em,
blockquote i,
blockquote cite {
  font-style: normal;
}
blockquote strong,
blockquote b {
  font-weight: 400;
}
address {
  font-style: italic;
  margin: 0 0 1.6em;
}
code,
kbd,
tt,
var,
samp,
pre {
  font-family: Inconsolata, monospace;
  -webkit-hyphens: none;
  -moz-hyphens: none;
  -ms-hyphens: none;
  hyphens: none;
}
pre {
  background-color: transparent;
  background-color: rgba(0, 0, 0, 0.01);
  border: 1px solid #eaeaea;
  border: 1px solid rgba(51, 51, 51, 0.1);
  line-height: 1.2;
  margin-bottom: 1.6em;
  max-width: 100%;
  overflow: auto;
  padding: 0.8em;
  white-space: pre;
  white-space: pre-wrap;
  word-wrap: break-word;
}
abbr[title] {
  border-bottom: 1px dotted #eaeaea;
  border-bottom: 1px dotted rgba(51, 51, 51, 0.1);
  cursor: help;
}
mark,
ins {
  background-color: #fff9c0;
  text-decoration: none;
}
sup,
sub {
  font-size: 75%;
  height: 0;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  bottom: 1ex;
}
sub {
  top: .5ex;
}
small {
  font-size: 75%;
}
big {
  font-size: 125%;
}
hr {
  background-color: #eaeaea;
  background-color: rgba(51, 51, 51, 0.1);
  border: 0;
  height: 1px;
  margin: 15px 0;
}
ul,
ol {
  margin: 0;
  padding: 0;
}
ul {
  list-style: none;
}
ol {
  list-style: none;
}
li > ul,
li > ol {
  margin-bottom: 0;
}
table,
th,
td {
  border: 1px solid #eaeaea;
  border: 1px solid rgba(51, 51, 51, 0.1);
}
table {
  border-collapse: separate;
  border-spacing: 0;
  border-width: 1px 0 0 1px;
  margin: 0 0 1.6em;
  table-layout: fixed;
  /* Prevents HTML tables from becoming too wide */
  width: 100%;
}
caption,
th,
td {
  font-weight: normal;
  text-align: left;
}
th {
  border-width: 0 1px 1px 0;
  font-weight: 700;
}
td {
  border-width: 0 1px 1px 0;
}
th,
td {
  padding: 0.4em;
}
img {
  -ms-interpolation-mode: bicubic;
  border: 0;
  height: auto;
  max-width: 100%;
  vertical-align: middle;
}
figure {
  margin: 0;
  max-width: 100%;
}
del {
  opacity: 0.8;
}
/* Placeholder text color -- selectors need to be separate to work. */
::-webkit-input-placeholder {
  color: rgba(51, 51, 51, 0.7);
font-family: 'Tajawal', sans-serif;}
:-moz-input-placeholder {
  color: rgba(51, 51, 51, 0.7);
font-family: 'Tajawal', sans-serif;}
::-moz-input-placeholder {
  color: rgba(51, 51, 51, 0.7);
font-family: 'Tajawal', sans-serif;  opacity: 1;
  /* Since FF19 lowers the opacity of the placeholder by default */
}
:-ms-input-placeholder {
  color: rgba(51, 51, 51, 0.7);
font-family: 'Tajawal', sans-serif;}
textarea {
  max-width: 100%;
}
a {
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
a:hover {
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
/* III. COMPONENT
***********************/
/***************** Menu ******************/
.wrapper-small {
  max-width: 728px;
}
.nav-container {
  z-index: 9999;
  overflow-y: auto;
  visibility: hidden;
  /* 2 */
  width: 100%;
  -webkit-transition: all 0.25s cubic-bezier(0.645, 0.045, 0.355, 1) 0s;
  transition: all 0.25s cubic-bezier(0.645, 0.045, 0.355, 1) 0s;
  -webkit-transform: translateX(-100%);
  -ms-transform: translateX(-100%);
  transform: translateX(-100%);
  /* 2 */
  -webkit-overflow-scrolling: touch;
  /* 3 */
}
/* 1. Show when `.is-visible` class is added */
.nav-container.is-visible {
  background: #000;
  visibility: visible;
  /* 1 */
  -webkit-transform: translateX(0);
  -ms-transform: translateX(0);
  transform: translateX(0);
  /* 1 */
}
.nav-container.is-visible .menu-item {
  overflow: hidden;
  border-bottom: 1px dashed #303030;
}
.nav-container.is-visible .menu-item:last-child {
  border-bottom: 0!important;
}
.nav-container.is-visible .menu-item .menu-link {
  color: #ffffff;
  padding: 10px 15px;
  width: 100%;
}
.nav-container.is-visible .menu-item .menu-link.set_active {
  color: #0567FA;
}
.nav-container.is-visible .menu-item .menu-link + .sub_active {
  color: #0567FA;
}
.nav-container.is-visible .menu-item:hover {
  color: #0567FA;
}
/* Nav toggle */
.nav-toggle {
  cursor: pointer;
  line-height: 1;
  display: inline-block;
  padding: 1.25rem 1rem;
  border: 0;
  background-color: #e74c3c;
  position: absolute;
  right: 0;
}
/* Nav toggle icon */
.nav-toggle .icon-menu {
  position: relative;
  display: inline-block;
  width: 28px;
  height: 20px;
  vertical-align: middle;
  fill: none;
}
/* Nav toggle icon lines */
.icon-menu .line {
  position: absolute;
  left: 0;
  display: block;
  width: 100%;
  height: 4px;
  -webkit-transition: all 0.25s cubic-bezier(0.645, 0.045, 0.355, 1);
  transition: all 0.25s cubic-bezier(0.645, 0.045, 0.355, 1);
  -webkit-transition-timing-function: cubic-bezier(0.645, 0.045, 0.355, 1);
  transition-timing-function: cubic-bezier(0.645, 0.045, 0.355, 1);
  background-color: #fff;
}
/* Nav toggle icon line 1 */
.icon-menu .line-1 {
  top: 0;
}
/* When active, rotate line 1 to be lefthand part of X */
.is-active .icon-menu .line-1 {
  -webkit-transform: translateY(8px) translateX(0) rotate(45deg);
  -ms-transform: translateY(8px) translateX(0) rotate(45deg);
  transform: translateY(8px) translateX(0) rotate(45deg);
}
/* Nav toggle icon line 2 */
.icon-menu .line-2 {
  top: 50%;
  margin-top: -2px;
}
/* When active, hide line 2 */
.is-active .icon-menu .line-2 {
  opacity: 0;
}
/* Nav toggle icon line 3 */
.icon-menu .line-3 {
  bottom: 0;
}
/* When active, rotate line 3 to be righthand part of X */
.is-active .icon-menu .line-3 {
  -webkit-transform: translateY(-8px) translateX(0) rotate(-45deg);
  -ms-transform: translateY(-8px) translateX(0) rotate(-45deg);
  transform: translateY(-8px) translateX(0) rotate(-45deg);
}
.nav-menu {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* 2 */
}
.nav-menu .menu-link {
  display: block;
  /* 1 */
  color: #303030;
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  margin-right: 13px;
  cursor: pointer;
}
.nav-menu .menu-link:hover {
  color: #f10027;
}
/* 1. Menu items with dropdowns appear clickable */
.has-dropdown {
  position: relative;
  cursor: pointer;
  /* 1 */
}
/* 1. Parent menu links inlined so you can toggle the dropdown */
.has-dropdown > .menu-link {
  display: inline-block;
}
/* 1. Add an icon to menu items that have sub menus */
.has-dropdown:after {
  font-size: 32px;
  position: absolute;
  top: 0;
  right: 1rem;
  bottom: 0;
  content: "+";
  /* 1 */
  color: #0567FA;
}
/* 1. Switch icon to n-dash when toggled */
.has-dropdown.is-active:after {
  content: "\2013";
  /* 1 */
}
.nav-dropdown {
  display: none;
  /* 1 */
}
.nav-dropdown .menu-item {
  border-bottom: 1px dashed #303030 !important;
}
/* 1. Show dropdown when toggled */
.has-dropdown.is-active > .nav-dropdown {
  display: block;
}
.is-active > .menu-link {
  color: #0567FA;
}
/* 2nd level dropdown */
.nav-dropdown .nav-dropdown {
  background-color: #aaa;
}
.nav-dropdown .menu-item {
  border-color: #a0a0a0;
}
.nav-dropdown .nav-dropdown .menu-item {
  background-color: #b0b0b0;
  border-color: #909090;
}
.nav {
  position: relative;
  text-align: left;
  height: 60px;
}
@media (min-width: 992px) {
  .v2_header .nav {
    position: relative;
    left: 0;
  }
  .nav {
    transition-duration: 0.5s;
    -webkit-transition-duration: 0.5s;
    -moz-transition-duration: 0.5s;
    -o-transition-duration: 0.5s;
    position: absolute;
    left: 472px;
    z-index: 10;
  }
  .nav,
  .nav-container,
  .nav-container.is-visible {
    -webkit-transform: translateX(0);
    -ms-transform: translateX(0);
    transform: translateX(0);
  }
  .nav-container,
  .nav-container.is-visible {
    visibility: visible;
    height: auto;
    min-height: 0;
    overflow-y: visible;
  }
  .nav-toggle {
    display: none;
  }
  /* 1. Display menu items inline */
  .nav-menu > .menu-item,
  .nav-menu > .menu-item.is-active {
    display: inline-block;
    /* 1 */
    background-color: transparent;
    border: 0;
  }
  /* Remove bottom border on last child */
  .nav-menu > .menu-item:last-child {
    border: 0;
  }
  .nav-menu .menu-item {
    -webkit-transition: background-color 0.15s ease-in-out, color 0.15s ease-in-out;
    transition: background-color 0.15s ease-in-out, color 0.15s ease-in-out;
  }
  .nav-menu > .menu-item > .menu-link:after {
    content: url(../images/menu_at.png);
    display: block;
    position: relative;
    top: 6px;
  }
  .nav-menu .set_active {
    color: #0567FA !important;
  }
  .nav-menu .set_active:after {
    content: url(../images/menu_active.png) !important;
    display: block;
    text-align: center;

  }
    .nav-menu .set_active2:Before {
    content: url(../images/ct_bl.png) !important;
    display: block;
    text-align: center;
  }
  /* Remove +/- icons */
  .has-dropdown:after {
    content: "" !important;
  }
  /* Re-style dropdowns for larger screens */
  .nav-dropdown {
    visibility: hidden;
    display: block;
    opacity: 0;
    position: absolute;
    top: 250%;
    min-width: 180px;
    left: -15px;
    margin: 0;
    padding-top: 32px;
    transition-duration: 0.2s;
    -webkit-transition-duration: 0.2s;
    -moz-transition-duration: 0.2s;
  }
  .nav-dropdown .menu-item {
    border-bottom: 1px dashed #ffffff !important;
    background: #0567FA;
    border: 0!important;
    float: left;
    width: 100%;
  }
  .nav-dropdown .menu-item:last-of-type .menu-link {
    border-bottom: 0!important;
  }
  .nav-dropdown .menu-item .menu-link {
    border-bottom: 1px dashed #ffffff;
    color: #ffffff;
    padding: 15px;
    float: left;
    width: 100%;
  }
  .nav-dropdown .menu-item .menu-link:hover {
    color: #0567FA;
    background: #ffffff;
  }
  .has-dropdown:hover > .nav-dropdown {
    visibility: visible;
    opacity: 1;
    z-index: 2;
    top: 100%;
    transition-duration: 0.3s;
    -webkit-transition-duration: 0.3s;
    -moz-transition-duration: 0.3s;
  }
  [data-uk-sticky].uk-active .nav-dropdown {
    padding-top: 13px;
  }
  .nav-dropdown .menu-item {
    border: 0;
  }
  .nav-dropdown .nav-dropdown,
  .nav-dropdown .nav-dropdown .menu-item {
    background-color: #dedede;
  }
  .nav-dropdown .nav-dropdown {
    z-index: 9998;
    top: 0;
    left: 100%;
  }
}
/*************** End Menu*****************/
/*****************  Slider *******************/
.bx-wrapper {
  position: relative;
  *zoom: 1;
}
.bx-wrapper img {
  max-width: 100%;
  display: block;
}
/** THEME
===================================*/
.bx-wrapper .bx-viewport {
  /*fix other elements on the page moving (on Chrome)*/
  -webkit-transform: translatez(0);
  -moz-transform: translatez(0);
  -ms-transform: translatez(0);
  -o-transform: translatez(0);
  transform: translatez(0);
  bottom: -140px;
}
.bx-wrapper .bx-pager,
.bx-wrapper .bx-controls-auto {
  position: absolute;
  bottom: -30px;
  width: 100%;
}
/* LOADER */
.bx-wrapper .bx-loading {
  min-height: 50px;
  /*background: url(images/bx_loader.gif) center center no-repeat #fff;*/
  height: 100%;
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
  z-index: 2000;
}
/* PAGER */
.bx-wrapper .bx-pager {
  text-align: center;
  font-size: .85em;
  font-family: Arial;
  font-weight: bold;
  color: #666;
  padding-top: 20px;
}
.bx-wrapper .bx-pager .bx-pager-item,
.bx-wrapper .bx-controls-auto .bx-controls-auto-item {
  display: inline-block;
  *zoom: 1;
  *display: inline;
}
.bx-wrapper .bx-pager.bx-default-pager a {
  background: #666;
  text-indent: -9999px;
  display: block;
  width: 10px;
  height: 10px;
  margin: 0 5px;
  outline: 0;
  -moz-border-radius: 5px;
  -webkit-border-radius: 5px;
  border-radius: 5px;
}
.bx-wrapper .bx-pager.bx-default-pager a:hover,
.bx-wrapper .bx-pager.bx-default-pager a.active {
  background: #000;
}
/* DIRECTION CONTROLS (NEXT / PREV) */
@media (max-width: 991px) {
  .bx-controls {
    left: 0!important;
    top: 50px;
  }
  .bx-controls .bx-controls-direction {
    bottom: inherit;
  }
}
.bx-controls {
  position: absolute;
  left: -52%;
}
.bx-controls-direction {
  position: absolute;
  bottom: 111px;
  width: 100%;
  z-index: 10;
}
.bx-wrapper .bx-prev {
  z-index: 10;
}
.bx-wrapper .bx-prev:before {
  content: "\f3d2";
}
.bx-wrapper .bx-next {
  z-index: 10;
  left: 68px;
}
.bx-wrapper .bx-next:before {
  content: "\f3d3";
}
.bx-wrapper .bx-prev:hover {
  background-position: 0 0;
}
.bx-wrapper .bx-next:hover {
  background-position: -43px 0;
}
.bx-wrapper .bx-controls-direction a {
  position: absolute;
  outline: 0;
  width: 48px;
  height: 48px;
  font-size: 0;
  z-index: 9999;
  border: 1px dashed #dd6726;
  border-radius: 50%;
  text-align: center;
  line-height: 46px;
}
.bx-wrapper .bx-controls-direction a:before {
  font-family: "ionicons";
  font-size: 24px;
  color: #dd6726;
}
.bx-wrapper .bx-controls-direction a.disabled {
  display: none;
}
/* PAGER WITH AUTO-CONTROLS HYBRID LAYOUT */
.bx-wrapper .bx-controls.bx-has-controls-auto.bx-has-pager .bx-pager {
  text-align: left;
  width: 80%;
}
.bx-wrapper .bx-controls.bx-has-controls-auto.bx-has-pager .bx-controls-auto {
  right: 0;
  width: 35px;
}
/***************** End  Slider ******************/
.smk_accordion {
  position: relative;
}
.smk_accordion .accordion_in {
  position: relative;
  z-index: 2;
  overflow: hidden;
}
.smk_accordion .accordion_in .acc_head .acc_icon_expand {
  display: block;
  position: absolute;
  right: 20px;
}
.smk_accordion .accordion_in .acc_head .acc_icon_expand:before {
  content: "\f2c7";
  font-family: "ionicons";
  font-size: 18px;
  color: #0567FA;
}
.smk_accordion .accordion_in.acc_active > .acc_content {
  display: block;
}
.acc_active .acc_head {
  background: #0567FA!important;
}
.accordion_in {
  margin-bottom: 1px;
}
.acc_head {
  border-radius: 50px;
  border: 1px solid #f0f0f0;
  height: 48px;
  line-height: 46px;
  font-size: 16px;
  color: #777;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  text-transform: uppercase;
  position: relative;
  cursor: pointer;
  padding-left: 20px;
}
.acc_head span {
  margin-right: 9px;
}
.acc_content {
  background: #fef8f4;
  margin-top: -24px;
  padding-bottom: 25px;
  padding-top: 50px;
  padding-left: 82px;
  padding-right: 50px;
  border: 1px solid #fefefe;
}
.acc_content li {
  line-height: 24px;
  color: #777;
  position: relative;
  margin-bottom: 10px;
}
.acc_content li:before {
  font-family: "ionicons";
  position: absolute;
  left: -20px;
  font-size: 16px;
  color: #f10027;
}
.acc_content li:nth-child(1):before {
  content: "\f35a";
}
.acc_content li:nth-child(2):before {
  content: "\f391";
}
.acc_content li:nth-child(3):before {
  content: "\f2d1";
}
.acc_content li:nth-child(4):before {
  content: "\f2d3";
}
.acc_content li:nth-child(5):before {
  content: "\f2e3";
}
.smk_accordion .accordion_in.acc_active > .acc_head {
  color: #ffffff;
}
.smk_accordion .accordion_in.acc_active > .acc_head .acc_icon_expand:before {
  content: "\f209";
  color: #ffffff;
}
/* Slider */
.slick-slider {
  position: relative;
  display: block;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  -webkit-touch-callout: none;
  -khtml-user-select: none;
  -ms-touch-action: pan-y;
  touch-action: pan-y;
  -webkit-tap-highlight-color: transparent;
}
.slick-list {
  position: relative;
  display: block;
  overflow: hidden;
  margin: 0;
  padding: 0;
}
.slick-list:focus {
  outline: none;
}
.slick-list.dragging {
  cursor: pointer;
  cursor: hand;
}
.slick-slider .slick-track,
.slick-slider .slick-list {
  -webkit-transform: translate3d(0, 0, 0);
  -moz-transform: translate3d(0, 0, 0);
  -ms-transform: translate3d(0, 0, 0);
  -o-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
}
.slick-track {
  position: relative;
  top: 0;
  left: 0;
  display: block;
}
.slick-track:before,
.slick-track:after {
  display: table;
  content: '';
}
.slick-track:after {
  clear: both;
}
.slick-loading .slick-track {
  visibility: hidden;
}
.slick-slide {
  display: none;
  float: left;
  height: 100%;
  min-height: 1px;
}
[dir='rtl'] .slick-slide {
  float: right;
}
.slick-slide img {
  display: block;
}
.slick-slide.slick-loading img {
  display: none;
}
.slick-slide.dragging img {
  pointer-events: none;
}
.slick-initialized .slick-slide {
  display: block;
}
.slick-loading .slick-slide {
  visibility: hidden;
}
.slick-vertical .slick-slide {
  display: block;
  height: auto;
  border: 1px solid transparent;
}
.slick-arrow.slick-hidden {
  display: none;
}
.flex-container a:hover,
.flex-slider a:hover {
  outline: none;
}
.slides,
.slides > li,
.flex-control-nav,
.flex-direction-nav {
  margin: 0;
  padding: 0;
  list-style: none;
}
.flex-pauseplay span {
  text-transform: capitalize;
}
/* ====================================================================================================================
* BASE STYLES
* ====================================================================================================================*/
.flexslider {
  margin: 0;
  padding: 0;
}
.flexslider .slides > li {
  display: none;
  -webkit-backface-visibility: hidden;
}
.flexslider .slides img {
  width: 100%;
  display: block;
}
.flexslider .slides:after {
  content: "\0020";
  display: block;
  clear: both;
  visibility: hidden;
  line-height: 0;
  height: 0;
}
html[xmlns] .flexslider .slides {
  display: block;
}
* html .flexslider .slides {
  height: 1%;
}
.no-js .flexslider .slides > li:first-child {
  display: block;
}
.gallery #slider {
  overflow: hidden;
}
.gallery #slider .flex-viewport {
  height: 472px;
  border-radius: 20px;
  z-index: 1;
}
.gallery #slider .flex-viewport .slides {
  z-index: 2;
}
.gallery #slider .flex-viewport:before {
  content: "";
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  position: absolute;
  border: 10px solid rgba(255, 255, 255, 0.5);
  z-index: 1;
  border-radius: 20px;
}
.gallery #slider .flex-direction-nav .flex-next {
  margin-top: -35px;
}
.gallery #slider .flex-direction-nav .flex-next:before {
  content: "\f3d3";
  font-family: "ionicons";
  font-size: 70px;
  color: #ffffff;
}
.gallery #slider .flex-direction-nav .flex-prev {
  margin-top: -35px;
}
.gallery #slider .flex-direction-nav .flex-prev:before {
  content: "\f3d2";
  font-family: "ionicons";
  font-size: 70px;
  color: #ffffff;
}
.gallery #carousel {
  overflow: hidden;
}
.gallery #carousel .slides li {
  border: 5px solid #f6f6f6;
  border-radius: 5px;
  width: 90px!important;
  height: 90px;
}
.gallery #carousel .slides li img {
  width: 100%;
  height: 100%;
}
.gallery #carousel .flex-direction-nav .flex-next {
  margin-top: -20px;
}
.gallery #carousel .flex-direction-nav .flex-next:before {
  content: "\f3d3";
  font-family: "ionicons";
  font-size: 40px;
  color: #303030;
  font-weight: 900;
}
.gallery #carousel .flex-direction-nav .flex-prev {
  margin-top: -20px;
}
.gallery #carousel .flex-direction-nav .flex-prev:before {
  content: "\f3d2";
  font-family: "ionicons";
  font-size: 40px;
  color: #303030;
  font-weight: 900;
}
.flexslider {
  position: relative;
  margin-bottom: 20px;
}
.flexslider .slides {
  zoom: 1;
}
.flexslider .slides img {
  height: auto;
  -moz-user-select: none;
}
.flex-viewport {
  max-height: 2000px;
  -webkit-transition: all 1s ease;
  -moz-transition: all 1s ease;
  -ms-transition: all 1s ease;
  -o-transition: all 1s ease;
  transition: all 1s ease;
}
.loading .flex-viewport {
  max-height: 300px;
}
.carousel li {
  margin-right: 5px;
}
.flex-direction-nav {
  *height: 0;
}
.flex-direction-nav a {
  text-decoration: none;
  display: block;
  position: absolute;
  top: 50%;
  z-index: 10;
  font-size: 0;
  overflow: hidden;
  opacity: 1;
  cursor: pointer;
  -webkit-transition: all 0.3s ease-in-out;
  -moz-transition: all 0.3s ease-in-out;
  -ms-transition: all 0.3s ease-in-out;
  -o-transition: all 0.3s ease-in-out;
  transition: all 0.3s ease-in-out;
}
.flex-direction-nav .flex-prev {
  left: -50px;
}
.flex-direction-nav .flex-next {
  right: -50px;
  text-align: right;
}
.flexslider:hover .flex-direction-nav .flex-prev {
  opacity: 0.8;
  left: 20px;
}
.flexslider:hover .flex-direction-nav .flex-prev:hover {
  opacity: 1;
}
.flexslider:hover .flex-direction-nav .flex-next {
  opacity: 0.8;
  right: 20px;
}
.flexslider:hover .flex-direction-nav .flex-next:hover {
  opacity: 1;
}
.flex-direction-nav .flex-disabled {
  opacity: 0!important;
  filter: alpha(opacity=0);
  cursor: default;
  z-index: -1;
}
.flex-control-nav {
  width: 100%;
  position: absolute;
  bottom: -40px;
  text-align: center;
}
.flex-control-nav li {
  margin: 0 6px;
  display: inline-block;
  zoom: 1;
  *display: inline;
}
.flex-control-thumbs {
  margin: 5px 0 0;
  position: static;
  overflow: hidden;
}
.flex-control-thumbs li {
  width: 25%;
  float: left;
  margin: 0;
}
.flex-control-thumbs img {
  width: 100%;
  height: auto;
  display: block;
  opacity: .7;
  cursor: pointer;
  -moz-user-select: none;
  -webkit-transition: all 1s ease;
  -moz-transition: all 1s ease;
  -ms-transition: all 1s ease;
  -o-transition: all 1s ease;
  transition: all 1s ease;
}
.flex-control-thumbs img:hover {
  opacity: 1;
}
.flex-control-thumbs .flex-active {
  opacity: 1;
  cursor: default;
}
@media screen and (max-width: 860px) {
  .flex-direction-nav .flex-prev {
    opacity: 1;
    left: 20px;
  }
  .flex-direction-nav .flex-next {
    opacity: 1;
    right: 20px;
  }
}
.uk-panel {
  display: block;
  position: relative;
}
[data-uk-sticky][class*=uk-animation-] {
  -webkit-animation-duration: 0.3s;
  animation-duration: 0.3s;
}
[data-uk-sticky].uk-active {
  z-index: 980;
}
.uk-panel > :not(.uk-panel-title):last-child {
  margin-bottom: 0;
}
.uk-animation-slide-bottom {
  -webkit-animation-name: uk-fade-bottom;
  animation-name: uk-fade-bottom;
}
.uk-animation-slide-top {
  -webkit-animation-name: uk-fade-top;
  animation-name: uk-fade-top;
}
.uk-animation-slide-top {
  -webkit-animation-name: uk-fade-top;
  animation-name: uk-fade-top;
}
.uk-animation-slide-bottom {
  -webkit-animation-name: uk-fade-bottom;
  animation-name: uk-fade-bottom;
}
.uk-animation-reverse {
  -webkit-animation-direction: reverse;
  animation-direction: reverse;
  -webkit-animation-timing-function: ease-in;
  animation-timing-function: ease-in;
}
[class*=uk-animation-] {
  -webkit-animation-duration: .5s;
  animation-duration: .5s;
  -webkit-animation-timing-function: ease-out;
  animation-timing-function: ease-out;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
}
.uk-panel:after {
  content: "";
  display: table;
}
.uk-panel:after {
  content: "";
  display: table;
  clear: both;
}
[class*=uk-animation-] {
  -webkit-animation-duration: .5s;
  animation-duration: .5s;
  -webkit-animation-timing-function: ease-out;
  animation-timing-function: ease-out;
  -webkit-animation-fill-mode: both;
  animation-fill-mode: both;
}
@media screen {
  [data-uk-scrollspy*=uk-animation-]:not([data-uk-scrollspy*=target]) {
    opacity: 0;
  }
}
.uk-animation-fade {
  -webkit-animation-name: uk-fade;
  animation-name: uk-fade;
  -webkit-animation-duration: .8s;
  animation-duration: .8s;
  -webkit-animation-timing-function: linear!important;
  animation-timing-function: linear !important;
}
.uk-animation-scale-up {
  -webkit-animation-name: uk-fade-scale-02;
  animation-name: uk-fade-scale-02;
}
.uk-animation-scale-down {
  -webkit-animation-name: uk-fade-scale-18;
  animation-name: uk-fade-scale-18;
}
.uk-animation-slide-top {
  -webkit-animation-name: uk-fade-top;
  animation-name: uk-fade-top;
}
.uk-animation-slide-bottom {
  -webkit-animation-name: uk-fade-bottom;
  animation-name: uk-fade-bottom;
}
.uk-animation-slide-left {
  -webkit-animation-name: uk-fade-left;
  animation-name: uk-fade-left;
}
.uk-animation-slide-right {
  -webkit-animation-name: uk-fade-right;
  animation-name: uk-fade-right;
}
.uk-animation-scale {
  -webkit-animation-name: uk-scale-12;
  animation-name: uk-scale-12;
}
.uk-animation-shake {
  -webkit-animation-name: uk-shake;
  animation-name: uk-shake;
}
.uk-animation-reverse {
  -webkit-animation-direction: reverse;
  animation-direction: reverse;
  -webkit-animation-timing-function: ease-in;
  animation-timing-function: ease-in;
}
.uk-animation-15 {
  -webkit-animation-duration: 15s;
  animation-duration: 15s;
}
.uk-animation-top-left {
  -webkit-transform-origin: 0 0;
  transform-origin: 0 0;
}
.uk-animation-top-center {
  -webkit-transform-origin: 50% 0;
  transform-origin: 50% 0;
}
.uk-animation-top-right {
  -webkit-transform-origin: 100% 0;
  transform-origin: 100% 0;
}
.uk-animation-middle-left {
  -webkit-transform-origin: 0 50%;
  transform-origin: 0 50%;
}
.uk-animation-middle-right {
  -webkit-transform-origin: 100% 50%;
  transform-origin: 100% 50%;
}
.uk-animation-bottom-left {
  -webkit-transform-origin: 0 100%;
  transform-origin: 0 100%;
}
.uk-animation-bottom-center {
  -webkit-transform-origin: 50% 100%;
  transform-origin: 50% 100%;
}
.uk-animation-bottom-right {
  -webkit-transform-origin: 100% 100%;
  transform-origin: 100% 100%;
}
.uk-animation-hover:not(:hover),
.uk-animation-hover:not(:hover) [class*=uk-animation-],
.uk-touch .uk-animation-hover:not(.uk-hover),
.uk-touch .uk-animation-hover:not(.uk-hover) [class*=uk-animation-] {
  -webkit-animation-name: none;
  animation-name: none;
}
@-webkit-keyframes uk-fade {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
@keyframes uk-fade {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
@-webkit-keyframes uk-fade-top {
  0% {
    opacity: 0;
    -webkit-transform: translateY(-100%);
  }
  100% {
    opacity: 1;
    -webkit-transform: translateY(0);
  }
}
@keyframes uk-fade-top {
  0% {
    opacity: 0;
    transform: translateY(-100%);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}
@-webkit-keyframes uk-fade-bottom {
  0% {
    opacity: 0;
    -webkit-transform: translateY(100%);
  }
  100% {
    opacity: 1;
    -webkit-transform: translateY(0);
  }
}
@keyframes uk-fade-bottom {
  0% {
    opacity: 0;
    transform: translateY(100%);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}
@-webkit-keyframes uk-fade-left {
  0% {
    opacity: 0;
    -webkit-transform: translateX(-100%);
  }
  100% {
    opacity: 1;
    -webkit-transform: translateX(0);
  }
}
@keyframes uk-fade-left {
  0% {
    opacity: 0;
    transform: translateX(-100%);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}
@-webkit-keyframes uk-fade-right {
  0% {
    opacity: 0;
    -webkit-transform: translateX(100%);
  }
  100% {
    opacity: 1;
    -webkit-transform: translateX(0);
  }
}
@keyframes uk-fade-right {
  0% {
    opacity: 0;
    transform: translateX(100%);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}
@-webkit-keyframes uk-fade-scale-02 {
  0% {
    opacity: 0;
    -webkit-transform: scale(0.2);
  }
  100% {
    opacity: 1;
    -webkit-transform: scale(1);
  }
}
@keyframes uk-fade-scale-02 {
  0% {
    opacity: 0;
    transform: scale(0.2);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}
@-webkit-keyframes uk-fade-scale-15 {
  0% {
    opacity: 0;
    -webkit-transform: scale(1.5);
  }
  100% {
    opacity: 1;
    -webkit-transform: scale(1);
  }
}
@keyframes uk-fade-scale-15 {
  0% {
    opacity: 0;
    transform: scale(1.5);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}
@-webkit-keyframes uk-fade-scale-18 {
  0% {
    opacity: 0;
    -webkit-transform: scale(1.8);
  }
  100% {
    opacity: 1;
    -webkit-transform: scale(1);
  }
}
@keyframes uk-fade-scale-18 {
  0% {
    opacity: 0;
    transform: scale(1.8);
  }
  100% {
    opacity: 1;
    transform: scale(1);
  }
}
@-webkit-keyframes uk-slide-left {
  0% {
    -webkit-transform: translateX(-100%);
  }
  100% {
    -webkit-transform: translateX(0);
  }
}
@keyframes uk-slide-left {
  0% {
    transform: translateX(-100%);
  }
  100% {
    transform: translateX(0);
  }
}
@-webkit-keyframes uk-slide-right {
  0% {
    -webkit-transform: translateX(100%);
  }
  100% {
    -webkit-transform: translateX(0);
  }
}
@keyframes uk-slide-right {
  0% {
    transform: translateX(100%);
  }
  100% {
    transform: translateX(0);
  }
}
@-webkit-keyframes uk-slide-left-33 {
  0% {
    -webkit-transform: translateX(33%);
  }
  100% {
    -webkit-transform: translateX(0);
  }
}
@keyframes uk-slide-left-33 {
  0% {
    transform: translateX(33%);
  }
  100% {
    transform: translateX(0);
  }
}
@-webkit-keyframes uk-slide-right-33 {
  0% {
    -webkit-transform: translateX(-33%);
  }
  100% {
    -webkit-transform: translateX(0);
  }
}
@keyframes uk-slide-right-33 {
  0% {
    transform: translateX(-33%);
  }
  100% {
    transform: translateX(0);
  }
}
@-webkit-keyframes uk-scale-12 {
  0% {
    -webkit-transform: scale(1.2);
  }
  100% {
    -webkit-transform: scale(1);
  }
}
@keyframes uk-scale-12 {
  0% {
    transform: scale(1.2);
  }
  100% {
    transform: scale(1);
  }
}
@-webkit-keyframes uk-rotate {
  0% {
    -webkit-transform: rotate(0);
  }
  100% {
    -webkit-transform: rotate(359deg);
  }
}
@keyframes uk-rotate {
  0% {
    transform: rotate(0);
  }
  100% {
    transform: rotate(359deg);
  }
}
@-webkit-keyframes uk-shake {
  0%,
  100% {
    -webkit-transform: translateX(0);
  }
  10% {
    -webkit-transform: translateX(-9px);
  }
  20% {
    -webkit-transform: translateX(8px);
  }
  30% {
    -webkit-transform: translateX(-7px);
  }
  40% {
    -webkit-transform: translateX(6px);
  }
  50% {
    -webkit-transform: translateX(-5px);
  }
  60% {
    -webkit-transform: translateX(4px);
  }
  70% {
    -webkit-transform: translateX(-3px);
  }
  80% {
    -webkit-transform: translateX(2px);
  }
  90% {
    -webkit-transform: translateX(-1px);
  }
}
@keyframes uk-shake {
  0%,
  100% {
    transform: translateX(0);
  }
  10% {
    transform: translateX(-9px);
  }
  20% {
    transform: translateX(8px);
  }
  30% {
    transform: translateX(-7px);
  }
  40% {
    transform: translateX(6px);
  }
  50% {
    transform: translateX(-5px);
  }
  60% {
    transform: translateX(4px);
  }
  70% {
    transform: translateX(-3px);
  }
  80% {
    transform: translateX(2px);
  }
  90% {
    transform: translateX(-1px);
  }
}
@-webkit-keyframes uk-slide-top-fixed {
  0% {
    opacity: 0;
    -webkit-transform: translateY(-10px);
  }
  100% {
    opacity: 1;
    -webkit-transform: translateY(0);
  }
}
@keyframes uk-slide-top-fixed {
  0% {
    opacity: 0;
    transform: translateY(-10px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}
@-webkit-keyframes uk-slide-bottom-fixed {
  0% {
    opacity: 0;
    -webkit-transform: translateY(10px);
  }
  100% {
    opacity: 1;
    -webkit-transform: translateY(0);
  }
}
@keyframes uk-slide-bottom-fixed {
  0% {
    opacity: 0;
    transform: translateY(10px);
  }
  100% {
    opacity: 1;
    transform: translateY(0);
  }
}
.rev_slider_wrapper {
  position: relative;
  z-index: 0;
}
.rev_slider {
  position: relative;
  overflow: visible;
}
.tp-overflow-hidden {
  overflow: hidden;
}
.tp-simpleresponsive img,
.rev_slider img {
  max-width: none !important;
  -moz-transition: none;
  -webkit-transition: none;
  -o-transition: none;
  transition: none;
  margin: 0px;
  padding: 0px;
  border-width: 0px;
  border: none;
}
.rev_slider .no-slides-text {
  font-weight: bold;
  text-align: center;
  padding-top: 80px;
}
.rev_slider > ul,
.rev_slider_wrapper > ul,
.tp-revslider-mainul > li,
.rev_slider > ul > li,
.rev_slider > ul > li:before,
.tp-revslider-mainul > li:before,
.tp-simpleresponsive > ul,
.tp-simpleresponsive > ul > li,
.tp-simpleresponsive > ul > li:before,
.tp-revslider-mainul > li,
.tp-simpleresponsive > ul > li {
  list-style: none !important;
  position: absolute;
  margin: 0px !important;
  padding: 0px !important;
  overflow-x: visible;
  overflow-y: visible;
  list-style-type: none !important;
  background-image: none;
  background-position: 0px 0px;
  text-indent: 0em;
  top: 0px;
  left: 0px;
}
.tp-revslider-mainul > li,
.rev_slider > ul > li,
.rev_slider > ul > li:before,
.tp-revslider-mainul > li:before,
.tp-simpleresponsive > ul > li,
.tp-simpleresponsive > ul > li:before,
.tp-revslider-mainul > li,
.tp-simpleresponsive > ul > li {
  visibility: hidden;
}
.tp-revslider-slidesli,
.tp-revslider-mainul {
  padding: 0 !important;
  margin: 0 !important;
  list-style: none !important;
}
.rev_slider li.tp-revslider-slidesli {
  position: absolute !important;
}
.tp-caption .rs-untoggled-content {
  display: block;
}
.tp-caption .rs-toggled-content {
  display: none;
}
.rs-toggle-content-active.tp-caption .rs-toggled-content {
  display: block;
}
.rs-toggle-content-active.tp-caption .rs-untoggled-content {
  display: none;
}
.rev_slider .tp-caption,
.rev_slider .caption {
  position: relative;
  visibility: hidden;
  white-space: nowrap;
  display: block;
}
.rev_slider .tp-mask-wrap .tp-caption,
.rev_slider .tp-mask-wrap *:last-child,
.wpb_text_column .rev_slider .tp-mask-wrap .tp-caption,
.wpb_text_column .rev_slider .tp-mask-wrap *:last-child {
  margin-bottom: 0;
}
/******************************
	-	IE8 HACKS	-
*******************************/
.noFilterClass {
  filter: none !important;
}
.tp-bannertimer {
  visibility: hidden !important;
}
.tparrows {
  cursor: pointer;
  width: 48px;
  height: 48px;
  position: absolute;
  display: block;
  z-index: 1000;
  border-radius: 50%;
  border: 1px dashed rgba(255, 255, 255, 0.3);
}
.tparrows:hover {
  border-color: #ffffff;
  transition-duration: 0.3s;
}
.tparrows:hover:before {
  color: #ffffff;
  transition-duration: 0.3s;
}
.tparrows:before {
  transition-duration: 0.3s;
  font-family: "ionicons";
  font-size: 24px;
  color: rgba(255, 255, 255, 0.3);
  display: block;
  line-height: 46px;
  text-align: center;
}
.tparrows.tp-leftarrow:before {
  content: "\f3d2";
}
.tparrows.tp-rightarrow:before {
  content: "\f3d3";
}
.row {
  *zoom: 1;
}
.row:before,
.row:after {
  content: " ";
  display: table;
}
.row:after {
  clear: both;
}
.row:before,
.row:after {
  content: " ";
  display: table;
}
.row:after {
  clear: both;
}
.row:before,
.row:after {
  content: " ";
  display: table;
}
.row:after {
  clear: both;
}
.row:before,
.row:after {
  content: " ";
  display: table;
}
.row:after {
  clear: both;
}
/* Text align
--------------------------*/
.text-center {
  text-align: center;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-justif {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
@media only screen and (min-width: 768px) {
  .text-right-sm {
    text-align: right;
  }
}
@media only screen and (min-width: 992px) {
  .text-right-md {
    text-align: right;
  }
}
.screen-reader-text,
.sr-only {
  clip: rect(1px, 1px, 1px, 1px);
  position: absolute !important;
  height: 1px;
  width: 1px;
  overflow: hidden;
}
select {
  border-radius: 0 !important;
  -webkit-border-radius: 0 !important;
}
/* IV. SKELETON
***********************/
/************************HEADER*************************/
#ht_header {
  height: 163px;
}
.top_section {
  border-top: 5px solid #F50A21;
  position: relative;
  z-index: 10;
}
.top_section .top_box {
  width: 930px;
  height: 39px;
  background: url(../images/cner.png) no-repeat top center;
  background-size: 100%;
  position: absolute;
  left: 0;
  padding: 0 94px;
  z-index: 1;
}
.top_section .top_box .top_list {
  position: relative;
  z-index: 10;
  top: 8px;
  float: right;
}
.top_section .top_box .top_list li {
  display: inline-block;
  color: #ffffff;
font-family: 'Tajawal', sans-serif;  font-size: 12px;
}
.top_section .top_box .top_list li.spc {
  margin-right: 25px;
}
.top_section .top_box .top_list li.spc:after {
  content: "";
  height: 20px;
  width: 2px;
  background: #84061A;
  float: right;
  margin-left: 25px;
}
.top_section .top_box .top_list li span {
  position: relative;
  top: 1px;
  color: #fff;
  margin-right: 11px;
  font-size: 20px;
  line-height: 1;
}
.top_section .top_box .top_list li a {
  font-family: Tajawal;
  color: #ffffff;
}
.top_section .top_box .top_list li a:hover {
  font-family: Tajawal;
  color: #f10027;
}
.top_section .top_box .top_list form input[type="text"] {
  color: #ffffff;
  font-family: Tajawal;
  background: #F50A21;
  border: 0;
  display: inline-table;
  padding: 0;
  font-size: 12px;
  width: inherit;
  width: 80px;
}
.top_section .top_box .top_list form button[type="submit"] {
  border: 0;
  font-family: Tajawal;
  background: transparent;
  cursor: pointer;
  position: relative;
  top: 2px;
}
.top_section .top_box .top_list form button[type="submit"]:before {
  content: "\f21f";
  font-family: "ionicons";
  color: #f10027;
  font-size: 14px;
}
.top_section .top_box .top_social {
  float: left;
  margin-top: 5px;
}
.top_section .top_box .top_social li {
  display: inline-block;
  margin-left: 0px;
}
.top_section .top_box .top_social li:first-of-type {
  margin-left: 0;
}
.top_section .top_box .top_social li a {
  color: #1783D6;
  font-size: 12px;
  width: 20px;
  height: 20px;
  background: #ffffff;
  border-radius: 50%;
  text-align: center;
  display: block;
  line-height: 20px;
  box-shadow: 10px 5px #cccccc -10px;
}
.top_section .top_box .top_social li a:hover {
  background: #f10027;
  color: #ffffff;
  transform: scale(1.2);
  -webkit-transform: scale(1.2);
  -moz-transform: scale(1.2);
}
.box_mn {
  height: 163px;
}
.top_menu {
  background: #fff;
  height: 163px;
  padding-top: 94px;
  float: left;
  width: 100%;
  z-index: 5;
}
.top_menu .lg {
  position: absolute;
    z-index: 5;
  width: 136px;
  height: 169px;
  top: 5px;
  right: 40px;
  transition-duration: 0s;
  -webkit-transition-duration: 0s;
  -moz-transition-duration: 0s;
}
.top_menu .lg img {
  width: 100$;
  height: 100%;


}
.top_menu .appoint {
  position: relative;
  z-index: 5;
  float: left;
  width: 150px;
  height: 40px;
  background: #f10027;
  color: #ffffff;
  text-transform: uppercase;
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  font-weight: 900;
  text-align: center;
  line-height: 40px;
  border-radius: 50px;
  border: 1px solid transparent;
  transition-duration: 0s;
  -webkit-transition-duration: 0s;
  -moz-transition-duration: 0s;
}
.top_menu .appoint2 {
  position: relative;
  z-index: 5;
  float: left;
  left: 5px;
  width: 150px;
  height: 40px;
  background: #1883d5;
  color: #ffffff;
  text-transform: uppercase;
  font-size: 14px;
  font-family: 'Tajawal', sans-serif;  font-weight: 900;
  text-align: center;
  line-height: 40px;
  border-radius: 50px;
  border: 1px solid transparent;
  transition-duration: 0s;
  -webkit-transition-duration: 0s;
  -moz-transition-duration: 0s;
}
.top_menu .appoint:hover {
  background: #ffffff;
  color: #0567FA;
  border-color: #0567FA;
}
.top_menu .appoint2:hover {
  background: #ffffff;
  color: #0567FA;
  border-color: #0567FA;
}

[data-uk-sticky].uk-active .top_menu {
  height: 60px;
  padding-top: 15px;
  box-shadow: 0 0 5px rgba(48, 48, 48, 0.5);
  -webkit-box-shadow: 0 0 5px rgba(48, 48, 48, 0.5);
  -moz-box-shadow: 0 0 5px rgba(48, 48, 48, 0.5);
}
[data-uk-sticky].uk-active .top_menu .lg {
  top: 5px;
  height: 50px;
  width: 94px;
}
[data-uk-sticky].uk-active .top_menu .appoint {
  line-height: 30px;
  height: 30px;
  font-size: 12px;
  width: 120px;
  font-weight: 400;
}
[data-uk-sticky].uk-active .top_menu .appoint2 {
  line-height: 30px;
  height: 30px;
  font-size: 12px;
  width: 120px;
  font-weight: 400;
}
.v2_header [data-uk-sticky].uk-active .top_menu {
  height: 60px;
  padding-top: 15px;
}
.v2_header [data-uk-sticky].uk-active .top_menu .li_lg .lg_block {
  position: relative;
  top: 10px;
}
.v2_header [data-uk-sticky].uk-active .top_menu .li_lg .lg_block img {
  width: 94px;
  height: 50px;
}
.v2_header [data-uk-sticky].uk-active .top_menu .calendar {
  top: -9px;
  z-index: 11;
}
.main_sl {
  overflow: hidden;
  border-top: 5px solid #e8e8e8;
  position: relative;
  margin-bottom: -240px;
}
.main_sl .box_sliders {
  position: relative;
}
.main_sl .box_sliders:before {
  content: "";
  display: block;
  position: absolute;
  left: 0;
  top: 100%;
  width: 0;
  height: 0;
  border-top: 59px solid transparent;
  border-bottom: 0 solid transparent;
  border-left: 315px solid #ffffff;
  z-index: 2;
  margin-top: -59px;
}
.main_sl .box_sliders:after {
  content: "";
  display: block;
  position: absolute;
  right: 0;
  top: 100%;
  width: 0;
  height: 0;
  border-top: 59px solid transparent;
  border-bottom: 0 solid transparent;
  border-right: 315px solid #ffffff;
  z-index: 2;
  margin-top: 59px;
}
.main_sl .box_sliders .tit_main {
font-family: 'Tajawal', sans-serif;  color: #ffffff;
  font-size: 15px;
  line-height: 1!important;
  border-bottom: 1px solid #ffffff !important;
  position: relative;
  min-height: 121px!important;
  padding-top: 25px!important;
}
.main_sl .box_sliders .tit_main:before {
  content: "";
  width: 30.77%;
  top: 0;
  left: 0;
  height: 1px;
  background: #ffffff;
  position: absolute;
}
.main_sl .box_sliders .tit_main:after {
  content: "";
  width: 30.77%;
  top: 0;
  right: 0;
  height: 1px;
  background: #ffffff;
  position: absolute;
}
.main_sl .box_sliders .tit_des {
font-family: 'Tajawal', sans-serif;  color: #ffffff;

}
.main_sl .box_sliders .tit_btn {
  text-align: center;
}
.main_sl .box_sliders .tit_btn .btn_go {
font-family: 'Tajawal', sans-serif;  color: #ffffff;

  text-transform: uppercase;
  padding: inherit!important;
  display: block;
  background: #0567FA;
  border-radius: 50px;
  margin-bottom: 5px!important;
  border: 1px solid transparent!important;
  transition: 0.5s!important;
}
.main_sl .box_sliders .tit_btn .btn_go:hover {
  border-color: #0567FA !important;
  background: #ffffff;
  color: #0567FA;
}
.main_sl .box_sliders .add_ {
  position: relative;
}
.main_sl .box_sliders .add_:after {
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  content: "";
  position: absolute;
  background: rgba(0, 0, 0, 0.4);
}
.main_sl .box_sliders .circle_text {
  color: #ffffff;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  padding: 7px 0!important;
}
.main_sl .box_sliders .title_main_2 {
font-family: 'Tajawal', sans-serif;  color: #ffffff;
}
.main_sl .box_sliders .title_main_2_cl {
font-family: 'Tajawal', sans-serif;  color: #0567FA;
}
.main_sl .box_sliders .welcome_ {
  color: #ffffff !important;
  font-family: "Grand Hotel", cursive;
  line-height: inherit!important;
}
.main_sl .box_sliders .welcome_ .big_1 {
  font-size: 35px;
  font-weight: normal;
}
.main_sl .box_sliders .welcome_ .big_2 {
  font-size: 30px;
  font-weight: normal;
}
.main_sl .box_sliders .welcome_ .big_3 {
  font-size: 100px;
  font-weight: normal;
}
.main_sl .box_sliders .tit_btn_2 {
  text-align: center!important;
}
.main_sl .box_sliders .tit_btn_2 .btn_go {
font-family: 'Tajawal', sans-serif;  color: #f10027;
  text-transform: uppercase;
  padding: inherit!important;
  display: block;
  margin-bottom: 5px!important;
  background: none;
  border-radius: 50px;
  border: 1px solid #f10027!important;
  transition: 0.5s!important;
}
.main_sl .box_sliders .tit_btn_2 .btn_go:before {
  content: "\f38e";
  font-size: 20px;
  margin-right: 15px;
  font-family: "ionicons";
  font-weight: normal;
}
.main_sl .box_sliders .tit_btn_2 .btn_go:hover {
  border-color: #ffffff !important;
  color: #ffffff;
}
.main_sl .box_sliders .tit_btn_3 {
  text-align: center!important;
}
.main_sl .box_sliders .tit_btn_3 .btn_go {
font-family: 'Tajawal', sans-serif;  color: #0567FA;
  text-transform: uppercase;
  display: block;
  margin-bottom: 10px!important;
  background: #ffffff;
  border-radius: 50px;
  border: 0!important;
  transition: 0.5s!important;
}
.main_sl .box_sliders .tit_btn_3 .btn_go:before {
  content: "\f38e";
  font-size: 20px;
  margin-right: 15px;
  font-family: "ionicons";
  font-weight: normal;
}
.main_sl .box_sliders .tit_btn_3 .btn_go:hover {
  color: #f10027;
}
.ht_footer .footer_ {
  min-height: 400px;
  background: url(../images/bg_footer.png) repeat-y top center;
  background-size: 100%;
  position: relative;
}
.ht_footer .footer_ .box_register {
  min-height: 145px;
  background: url(../images/reg.png) no-repeat bottom center;
  background-size: 100% 145px;
  margin-top: -80px;
  padding: 47px 60px;
}
.ht_footer .footer_ .box_register span {
  float: left;
  font-size: 24px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  color: #ffffff;
}
.ht_footer .footer_ .box_register a {
  float: right;
  width: 200px;
  height: 50px;
  border-radius: 50px;
  background: #ffffff;
  color: #f2722a;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  text-align: center;
  line-height: 50px;
  border: 1px solid transparent;
  font-size: 16px;
}
.ht_footer .footer_ .box_register a:hover {
  background: #0567FA;
  color: #ffffff;
  border: 1px solid #ffffff;
}
.ht_footer .footer_ .footer_main {
  margin-top: 29px;
  color: #ffffff;
  position: relative;
}
.ht_footer .footer_ .footer_main .des_ {
  border-radius: 10px;
  height: 131px;
  float: left;
  position: relative;
  margin-top: 30px;
}
.ht_footer .footer_ .footer_main .des_:after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  border: 3px solid rgba(107, 162, 173, 0.72);
  border-radius: 10px;
}
.ht_footer .footer_ .footer_main .des_ img {
  height: 100%;
  border-radius: 10px;
}
.ht_footer .footer_ .footer_main .lg_bottom:after {
  content: "";
  display: table;
  clear: both;
}
.ht_footer .footer_ .footer_main .info {
  margin-top: 20px;
}
.ht_footer .footer_ .footer_main .info li {
font-family: 'Tajawal', sans-serif;  font-size: 14px;
  color: #868686;
  line-height: 1;
  font-weight: 400;
  margin-bottom: 12px;
}

.ht_footer .footer_ .footer_main .info li:before {
  margin-right: 15px;
  font-family: "ionicons";
  line-height: 1;
  color: #0567FA;
  font-size: 16px;
}
.ht_footer .footer_ .footer_main .info li a {
font-family: 'Tajawal', sans-serif;  font-size: 14px;
  color: #868686;
  line-height: 1;
  font-weight: 400;
}
.ht_footer .footer_ .footer_main .info li a:hover {
  color: #0567FA;
}
.ht_footer .footer_ .footer_main h3 {
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  font-size: 24px;
  color: #ffffff;
  margin-top: 25px;
  float: right;
  width: 100%;
  margin-bottom: 25px;
}
.ht_footer .footer_ .footer_main .uselink li {
  border-bottom: 1px solid #383737;
  height: 39px;
  line-height: 33px;
}
.ht_footer .footer_ .footer_main .uselink li a {
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #868686;
  font-size: 14px;
}
.ht_footer .footer_ .footer_main .uselink li a:hover {
  color: #0567FA;
}
.ht_footer .footer_ .footer_main .uselink li a:before {
  content: "\f108";
    float: right;
  font-family: "ionicons";
  line-height: 2;
  color: #0567FA;
  margin-left: 15px;
}
.ht_footer .footer_ .footer_main .tw {
  float: right;
  width: 100%;
  margin-bottom: 5px;
}
.ht_footer .footer_ .footer_main .tw dt {
  float: right;
  width: 100%;
}
.ht_footer .footer_ .footer_main .tw dt p {
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  color: #868686;
  line-height: 24px;
  font-weight: 400;
}
.ht_footer .footer_ .footer_main .tw dt span {
  font-size: 14px;
  color: #555555;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  display: block;
  margin-top: 19px;
}
.ht_footer .footer_ .footer_main .tw dt span:before {
  content: "\f243";
  font-family: "ionicons";
  line-height: 1;
  margin-right: 10px;
}
.ht_footer .footer_ .footer_main .tw dd {
  float: left;
  width: 100%;
}
.ht_footer .footer_ .footer_main .tw dd a {
  font-size: 14px;
  color: #f2722a;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  font-style: italic;
}
.ht_footer .footer_ .footer_main .tw dd a:hover {
  text-decoration: underline;
}
.ht_footer .footer_ .footer_main .letter {
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  color: #868686;
  line-height: 24px;
  font-weight: 400;
  margin-bottom: 0;
}
.ht_footer .footer_ .footer_main .letter_form {
  margin-top: 23px;
}
.ht_footer .footer_ .footer_main .letter_form input {
  float: right;
  width: 100%;
  border: 0;
  border-radius: 50px;
  height: 50px;
  margin-bottom: 20px;
}
.ht_footer .footer_ .footer_main .letter_form input[type="text"] {
  background: #444444;
  padding: 0 35px;
  color: #0567FA;
  border: 1px solid transparent;
}
.ht_footer .footer_ .footer_main .letter_form input[type="text"]:focus {
  border: 1px solid #0567FA;
}
.ht_footer .footer_ .footer_main .letter_form input[type="text"]::-webkit-input-placeholder {
  color: #868686;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
}
.ht_footer .footer_ .footer_main .letter_form input[type="text"]::-moz-input-placeholder {
  color: #868686;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
}
.ht_footer .footer_ .footer_main .letter_form input[type="submit"] {
  cursor: pointer;
  background: #0567FA;
  text-transform: uppercase;
  color: #ffffff;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
}
.ht_footer .footer_ .footer_main .letter_form input[type="submit"]:hover {
  background: #f10027;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
}
.ht_footer .footer_ .box_social {
  position: absolute;
  bottom: 0;
  left: 0;
  text-align: center;
  height: 48px;
  display: block;
  border-bottom: 3px solid #F50A21;
}
.ht_footer .footer_ .box_social .footer_social {
  height: 45px;
  line-height: 45px;
  margin: 0 auto;
  position: relative;
  background: url(../images/shape_bottom.png) no-repeat bottom center;
}
.ht_footer .footer_ .box_social .footer_social li {
  display: inline-block;
  margin: 0 6.5px;
}
.ht_footer .footer_ .box_social .footer_social li a {
  font-size: 15px;
  color: #fff;
}
.ht_footer .footer_ .box_social .footer_social li a:hover {
  color: #999999;
  text-shadow: 1px 1px 1px color: #fff;
}
.ht_footer .copyright {
  min-height: 88px;
  background: #111;
  text-align: center;
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  line-height: 88px;
  color: #555555;
}
.ht_footer .copyright a {
  color: #0567FA;
font-family: 'Tajawal', sans-serif;}
.ht_footer .copyright a:hover {
  text-decoration: underline;
}
/* V. PART
***********************/
.hpage .v2_header#ht_header {
  height: 203px;
}
.hpage .v2_header .top_menu {
  height: 203px;
  padding-top: 47px;
}
.hpage .v2_header .top_menu .row {
  margin-left: -30px;
  margin-right: -30px;
}
.hpage .v2_header .top_menu [class*="col-"] {
  padding: 0;
}
.hpage .v2_header .top_menu .li_lg {
  position: relative;
  top: -22px;
  margin-right: 75px;
  margin-left: 62px;
}
.hpage .v2_header .top_menu .li_lg .lg_block img {
  width: 179px;
  height: 95px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
}
.hpage .v2_header .top_menu .lg {
  margin-right: inherit;
}
.hpage .v2_header .top_menu .lg.lg_none {
  display: none;
}
.hpage .v2_header .top_menu .menu-link {
  text-transform: uppercase;
  font-size: 13px;
  font-weight: 900;
}
.hpage .v2_header .top_menu .calendar {
  width: 48px;
  height: 48px;
  top: 5px;
  z-index: 11;
  border-radius: 50%;
  text-align: center;
  line-height: 48px;
  position: relative;
  float: right;
  background: #0567FA;
}
.hpage .v2_header .top_menu .calendar:before {
  content: "\f117";
  font-family: "ionicons";
  color: #ffffff;
  font-size: 19px;
}
.hpage .appointment {
  position: relative;
  min-height: 600px;
  padding-bottom: 118px;
  background: #ffffff;
}
.hpage .appointment .box_bear {
  position: absolute;
  width: 50%;
  padding: 100px;
  overflow: hidden;
}
.hpage .appointment .box_bear img {
  max-width: 100%;
}
.hpage .appointment .title_l h3 {
  font-size: 48px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  color: #303030;
  margin-top: 55px;
  margin-bottom: 10px;
}
.hpage .appointment .title_l h4 {
  font-size: 36px;
  font-family: "Grand Hotel", cursive;
  color: #0567FA;
  font-weight: 400;
}
.hpage .appointment .form_ {
  margin-top: 47px;
}
.hpage .appointment .form_ label {
  float: left;
  position: relative;
  margin-bottom: 15px;
  overflow: hidden;
}
.hpage .appointment .form_ label span {
  position: absolute;
  bottom: 0;
  height: 1px;
  width: 100%;
  display: block;
  left: -100%;
  background: #0567FA;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .appointment .form_ label:after {
  position: absolute;
  line-height: 1;
  font-family: "ionicons";
  right: 0;
  bottom: 21px;
  font-size: 18px;
  color: #ccc;
}
.hpage .appointment .form_ input[type="text"] {
  padding-right: 30px!important;
  float: left;
  width: 100%;
  border: 0;
  padding: 0;
  border-bottom: 1px solid #cccccc;
  height: 55px;
  font-size: 18px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #777;
  position: relative;
}
.hpage .appointment .form_ input[type="text"]:focus + span {
  left: 0;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .appointment .form_ input[type="text"]::-webkit-input-placeholder {
  color: #777777;
font-family: 'Tajawal', sans-serif;  font-style: italic;
  font-size: 18px;
  font-weight: 400;
}
.hpage .appointment .form_ input[type="text"]::-moz-placeholder {
  color: #777777;
font-family: 'Tajawal', sans-serif;  font-style: italic;
  font-size: 18px;
  font-weight: 400;
}
.hpage .appointment .form_ .name_ {
  width: 270px;
  margin-right: 30px;
}
.hpage .appointment .form_ .name_:after {
  content: "\f3a0";
}
.hpage .appointment .form_ .email_ {
  width: 370px;
}
.hpage .appointment .form_ .email_:after {
  content: "\f423";
}
.hpage .appointment .form_ .phone_ {
  width: 270px;
  margin-right: 30px;
}
.hpage .appointment .form_ .phone_:after {
  content: "\f3a2";
}
.hpage .appointment .form_ .date_ {
  width: 370px;
}
.hpage .appointment .form_ .date_:after {
  content: "\f3f3";
}
.hpage .appointment .form_ .msg_ {
  width: 100%;
  font-size: 18px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  font-style: italic;
  color: #777;
  margin-top: 14px;
}
.hpage .appointment .form_ .msg_:after {
  content: "\f11d";
  top: 48px;
  right: 10px;
  font-style: normal;
}
.hpage .appointment .form_ .msg_ textarea {
  resize: none;
  background: #f6f6f6;
  min-height: 110px;
  border: 0;
  margin-top: 13px;
  padding-right: 30px;
}
.hpage .appointment .form_ button {
  width: 160px;
  height: 40px;
  text-align: center;
  text-transform: uppercase;
  border-radius: 50px;
  border: 0;
  background: #0567FA;
  cursor: pointer;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  color: #ffffff;
  line-height: 40px;
  margin-top: 15px;
}
.hpage .home_pricing {
  text-align: center;
  margin-top: 127px;
}
.hpage .home_pricing .title_ h3 {
  font-size: 48px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  color: #303030;
  margin-bottom: 10px;
}
.hpage .home_pricing .title_ h4 {
  font-family: "Grand Hotel", cursive;
  color: #0567FA;
  font-weight: 400;
  font-size: 36px;
  margin-bottom: 23px;
}
.hpage .home_pricing .title_ p {
  font-size: 14px;
  color: #777;
  line-height: 24px;
  margin-bottom: 0;
}
.hpage .home_pricing .pricing_table {
  margin-top: 73px;
}
.hpage .home_pricing .item_pr {
  background: #f8f8f8;
  float: left;
  width: 100%;
  position: relative;
  min-height: 591px;
  margin-bottom: 140px;
}
.hpage .home_pricing .item_title {
  background: #f10027;
  height: 93px;
  float: left;
  width: 100%;
  position: relative;
}
.hpage .home_pricing .item_title:before {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  right: 0;
  background-repeat: repeat;
  height: 12px;
  background-size: 20px 20px;
  background-image: radial-gradient(circle at 10px -5px, transparent 14px, #f8f8f8 16px);
}
.hpage .home_pricing .item_title:after {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  right: 0;
  background-repeat: repeat;
  height: 12px;
  background-size: 40px 20px;
  background-image: radial-gradient(circle at 10px 15px, #f8f8f8 12px, transparent 13px);
}
.hpage .home_pricing .item_title span {
  font-size: 30px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  color: #ffffff;
  line-height: 93px;
}
.hpage .home_pricing .item_main {
  padding-top: 42px;
  float: left;
  width: 100%;
}
.hpage .home_pricing .item_main .icon_bug {
  height: 120px;
  width: 120px;
  display: block;
  border-radius: 50%;
  background: #ffffff;
  margin: 0 auto;
  -webkit-box-shadow: 0px 0px 35px 10px #e2e2e2;
  -moz-box-shadow: 0px 0px 35px 10px #e2e2e2;
  box-shadow: 0px 0px 35px 10px #e2e2e2;
}
.hpage .home_pricing .item_main .icon_bug:before {
  content: "\f2be";
  font-family: "ionicons";
  font-size: 60px;
  line-height: 120px;
  color: #0567FA;
}
.hpage .home_pricing .item_main .icon_bug_2:before {
  content: "\f3c2";
}
.hpage .home_pricing .item_main .icon_bug_3:before {
  content: "\f452";
}
.hpage .home_pricing .item_main .dot_ {
  float: left;
  width: 100%;
  margin-top: 9px;
}
.hpage .home_pricing .item_main .dot_ span {
  width: 5px;
  height: 5px;
  display: inline-block;
  background: #0567FA;
  border-radius: 50%;
  margin: 0 0.5px;
}
.hpage .home_pricing .item_main .dot_ dd {
  font-size: 36px;
  color: #303030;
  font-family: "Grand Hotel", cursive;
}
.hpage .home_pricing .item_main .dot_ .dtb {
  margin-top: -13px;
}
.hpage .home_pricing .item_main .list_ {
  float: left;
  width: 100%;
  margin-top: 24px;
}
.hpage .home_pricing .item_main .list_ li {
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #888;
  font-size: 16px;
  margin-bottom: 9px;
}
.hpage .home_pricing .item_main .list_ li b {
  color: #0567FA;
}
.hpage .home_pricing .item_bot {
  background: #f10027;
  height: 95px;
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  text-transform: uppercase;
  color: #ffffff;
  line-height: 95px;
}
.hpage .home_pricing .item_bot span {
  font-size: 22px;
  color: #ffffff;
  margin-right: 14px;
}
.hpage .home_pricing .item_bot:before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  transform: rotate(180deg);
  -webkit-transform: rotate(180deg);
  -moz-transform: rotate(180deg);
  right: 0;
  background-repeat: repeat;
  height: 12px;
  background-size: 20px 20px;
  background-image: radial-gradient(circle at 10px -5px, transparent 14px, #f8f8f8 16px);
}
.hpage .home_pricing .item_bot:after {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  transform: rotate(180deg);
  -webkit-transform: rotate(180deg);
  -moz-transform: rotate(180deg);
  right: 0;
  background-repeat: repeat;
  height: 12px;
  background-size: 40px 20px;
  background-image: radial-gradient(circle at 10px 15px, #f8f8f8 12px, transparent 13px);
}
.hpage .home_search_class {
  position: relative;
  min-height: 500px;
  overflow: hidden;
}
.hpage .home_search_class .left_ {
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  width: 50%;
}
.hpage .home_search_class .left_ img {
  width: 100%;
  height: 100%;
}
.hpage .home_search_class .right_ {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  width: 50%;
  background: #f10027;
}
.hpage .home_search_class .box_right {
  width: 100%;
  height: 100%;
  position: relative;
  padding-left: 55px;
  padding-bottom: 55px;
}
.hpage .home_search_class .box_right:before {
  transform: rotate(-90deg);
  content: "";
  position: absolute;
  left: -100%;
  margin-left: -12px;
  top: 50%;
  right: 0;
  background-repeat: repeat;
  height: 12px;
  background-size: 20px 20px;
  background-image: radial-gradient(circle at 10px -5px, transparent 14px, #f10027 16px);
}
.hpage .home_search_class .box_right:after {
  transform: rotate(-90deg);
  content: "";
  position: absolute;
  left: -100%;
  margin-left: -12px;
  top: 50%;
  right: 0;
  background-repeat: repeat;
  height: 12px;
  background-size: 40px 20px;
  background-image: radial-gradient(circle at 10px 15px, #f10027 12px, transparent 13px);
}
.hpage .home_search_class .title_l {
  padding-top: 64px;
}
.hpage .home_search_class .title_l h3 {
  font-size: 48px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  color: #ffffff;
  margin-bottom: 15px;
}
.hpage .home_search_class .title_l p {
  font-size: 14px;
  line-height: 24px;
  color: #ffffff;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
}
.hpage .home_search_class .form_ {
  margin-top: 36px;
}
.hpage .home_search_class .form_ label {
  float: left;
  width: 100%;
  height: 48px;
  position: relative;
  margin-bottom: 22px;
}
.hpage .home_search_class .form_ label select {
  height: 100%;
  border: 0;
  border-bottom: 1px solid #ffffff;
  background: #f10027;
  font-size: 18px;
font-family: 'Tajawal', sans-serif;  font-style: italic;
  font-weight: 400;
  color: #ffffff;
  padding: 0;
  margin: 0;
}
.hpage .home_search_class .form_ label input {
  height: 100%;
  background: #f10027;
  border: 0;
  border-bottom: 1px solid #ffffff;
  font-size: 18px;
font-family: 'Tajawal', sans-serif;  font-style: italic;
  font-weight: 400;
  color: #ffffff;
  padding: 0;
}
.hpage .home_search_class .form_ label input::-webkit-input-placeholder {
  font-size: 18px;
font-family: 'Tajawal', sans-serif;  font-style: italic;
  font-weight: 400;
  color: #ffffff;
}
.hpage .home_search_class .form_ label input::-moz-input-placeholder {
  font-size: 18px;
font-family: 'Tajawal', sans-serif;  font-style: italic;
  font-weight: 400;
  color: #ffffff;
}
.hpage .home_search_class .form_ button {
  width: 170px;
  height: 40px;
  border-radius: 100px;
  background: #ffffff;
  border: 0;
  text-align: center;
  line-height: 40px;
  color: #303030;
  text-transform: uppercase;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  cursor: pointer;
  float: left;
  margin-top: 28px;
  -webkit-box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.2);
  -moz-box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.2);
  box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.2);
}
.hpage .home_event {
  position: relative;
  background: #fefefe;
  padding-top: 122px;
  padding-bottom: 140px;
}
.hpage .home_event .class_title {
  text-align: center;
  margin-bottom: 70px;
}
.hpage .home_event .class_title h3 {
  font-size: 48px;
  color: #303030;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  margin-bottom: 15px;
}
.hpage .home_event .class_title h4 {
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  font-size: 36px;
  color: #0567FA;
  margin-bottom: 23px;
}
.hpage .home_event .class_title p {
  line-height: 24px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #303030;
  font-size: 14px;
}
.hpage .home_event .classes_it {
  margin-bottom: 70px;
  min-height: 576px;
  border-radius: 20px;
  transition-duration: 0.4s;
  -webkit-transition-duration: 0.4s;
  -moz-transition-duration: 0.4s;
}
.hpage .home_event .classes_it:hover {
  -webkit-box-shadow: 0px 0px 7px 0px rgba(0, 0, 0, 0.25);
  -moz-box-shadow: 0px 0px 7px 0px rgba(0, 0, 0, 0.25);
  box-shadow: 0px 0px 7px 0px rgba(0, 0, 0, 0.25);
  transition-duration: 0.4s;
  -webkit-transition-duration: 0.4s;
  -moz-transition-duration: 0.4s;
}
.hpage .home_event .classes_it:hover .box_suma {
  border-left-color: transparent;
  border-right-color: transparent;
}
.hpage .home_event .classes_it .box_img {
  position: relative;
  width: 100%;
  overflow: hidden;
  border-radius: 20px 20px 0 0;
  min-height: 347px;
}
.hpage .home_event .classes_it .box_img img {
  width: 100%;
}
.hpage .home_event .classes_it .box_img:before {
  position: absolute;
  content: "";
  left: 0;
  bottom: 0;
  width: 100%;
  height: 21px;
  background: url(../images/border.png) no-repeat bottom center;
  background-size: 100%;
}
.hpage .home_event .classes_it .box_img:after {
  position: absolute;
  content: "";
  left: 0;
  bottom: -31px;
  width: 100%;
  height: 107px;
  background: url(../images/shape_w.png) no-repeat top center;
  background-size: 100%;
}
.hpage .home_event .classes_it .box_suma {
  border-top: 0;
  padding-bottom: 78px;
  display: block;
  min-height: 232px;
  padding: 0 30px 39px 30px;
  border-radius: 0 0 20px 20px;
  position: relative;
  z-index: 5;
  background: #ffffff;
}
.hpage .home_event .classes_it .box_suma .date_ {
  margin-bottom: 7px;
}
.hpage .home_event .classes_it .box_suma .date_ span {
  float: left;
  font-size: 18px;
  font-family: "Grand Hotel", cursive;
  color: #0567FA;
  margin-right: 20px;
}
.hpage .home_event .classes_it .box_suma .date_ span:nth-of-type(1):before {
  content: "\f3f3";
  font-family: "ionicons";
  line-height: 1;
  font-size: 15px;
  color: #cccccc;
  margin-right: 5px;
}
.hpage .home_event .classes_it .box_suma .date_ span:nth-of-type(2):before {
  content: "\f3a0";
  font-family: "ionicons";
  line-height: 1;
  font-size: 15px;
  color: #cccccc;
  margin-right: 5px;
}
.hpage .home_event .classes_it .box_suma .name_ {
  font-size: 30px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  line-height: 1;
  color: #303030;
  margin-bottom: 9px;
  margin-top: 4px;
  white-space: nowrap;
}
.hpage .home_event .classes_it .box_suma .sumary_ {
  margin-top: 10px;
}
.hpage .home_event .classes_it .box_suma .sumary_ p {
  font-size: 14px;
  color: #303030;
  line-height: 24px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
}
.hpage .home_event .classes_it .box_suma .btn_readmore {
  color: #0567FA;
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  position: absolute;
  left: 31px;
  bottom: 39px;
}
.hpage .home_event .classes_it .box_suma .btn_readmore:after {
  content: "\f10b";
  margin-left: 5px;
  line-height: 1;
  font-family: "ionicons";
}
.hpage .home_event .all_items {
  text-transform: uppercase;
  color: #0567FA;
  border: 1px solid #0567FA;
  height: 50px;
  width: 170px;
  text-align: center;
  border-radius: 25px;
  display: block;
  margin: 0 auto;
  line-height: 48px;
}
.hpage .home_event .all_items:hover {
  background: #0567FA;
  color: #ffffff;
}
.hpage ._section_question {
  padding-top: 78px;
}
.hpage.hpage_2 .ht_footer {
  overflow: hidden;
  position: relative;
  padding-top: 80px;
}
.hpage.hpage_2 .footer_ {
  background: none;
}
.hpage.hpage_2 .footer_ .container {
  position: relative;
  z-index: 5;
}
.hpage.hpage_2 .footer_:before {
  content: "";
  background: url(../images/bg_footer.png) repeat-y top center;
  background-size: 100%;
  left: -50px;
  right: -50px;
  height: 100%;
  position: absolute;
  border-top-left-radius: 20%;
  border-top-right-radius: 20%;
}
.hpage .home_featured {
  padding: 120px 0 70px 0;
  background: #f8f8f8;
}
.hpage .home_featured .item_fea {
  text-align: center;
  margin-bottom: 50px;
}
.hpage .home_featured .fl {
  width: 178px;
  height: 183px;
  margin: 0 auto;
  position: relative;
}
.hpage .home_featured .fl:hover img {
  transform: rotate(45deg);
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .home_featured .fl img {
  position: absolute;
  left: 50%;
  margin-left: -89px;
  transition-duration: 0.2s;
  -moz-transition-duration: 0.2s;
  -webkit-transition-duration: 0.2s;
}
.hpage .home_featured .fl:before {
  font-family: "ionicons";
  line-height: 183px;
  font-size: 72px;
  color: #ffffff;
  position: relative;
  z-index: 1;
}
.hpage .home_featured .fl.flo:before {
  content: "\f2be";
}
.hpage .home_featured .fl.flt:before {
  content: "\f3c2";
}
.hpage .home_featured .fl.flth:before {
  content: "\f27d";
}
.hpage .home_featured .fl.flf:before {
  content: "\f3b0";
}
.hpage .home_featured .name_ {
  font-size: 30px;
  color: #303030;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  margin-top: 26px;
  margin-bottom: 9px;
}
.hpage .home_featured .name_ span {
  font-weight: 300;
}
.hpage .home_featured p {
  font-size: 14px;
  line-height: 22px;
  color: #777;
font-family: 'Tajawal', sans-serif;  margin-top: 7px;
}
.hpage ._section_classes {
  background: #ffffff;
}
.hpage .home_counter {
  background: #f8f8f8;
  padding: 120px 0 70px 0;
}
.hpage .home_counter .item_cter {
  position: relative;
  float: left;
  width: 100%;
  background: #0567FA;
  min-height: 180px;
  border-radius: 20px;
  padding: 27px 30px 39px 30px;
  overflow: hidden;
  margin-bottom: 50px;
}
.hpage .home_counter .item_cter:hover .img_cter {
  right: 0;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .home_counter .item_cter:hover .spc {
  right: -15px !important;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .home_counter .item_cter .name_ct {
  font-family: "Grand Hotel", cursive;
  color: #ffe2d3;
  font-size: 24px;
  font-weight: 400;
}
.hpage .home_counter .item_cter .space {
  height: 30px;
  width: 1px;
  background: #f7a97f;
  display: block;
  margin-left: 20px;
  margin-top: 10px;
}
.hpage .home_counter .item_cter .cter {
font-family: 'Tajawal', sans-serif;  font-weight: 900;
  color: #f9f9f9;
  font-size: 36px;
  position: absolute;
  left: 30px;
  bottom: 26px;
}
.hpage .home_counter .item_cter .cter.per:after {
  content: "%";
}
.hpage .home_counter .item_cter .cter.plus:after {
  content: "+";
  position: relative;
  top: -11px;
  font-size: 20px;
}
.hpage .home_counter .item_cter .img_cter {
  position: absolute;
  bottom: -10px;
  right: -10px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .home_counter .item_cter .img_cter.spc {
  bottom: -25px;
  right: -35px;
}
.hpage .subscribe {
  background: #f10027;
  padding: 70px 0;
}
.hpage .subscribe .box_left {
  position: relative;
}
.hpage .subscribe .box_left .mail_op {
  position: absolute;
  left: 0;
  top: -17px;
}
.hpage .subscribe .box_left .mail {
  float: left;
  margin-left: 60px;
  margin-right: 15px;
}
.hpage .subscribe .box_left .left_form {
  float: left;
  color: #ffffff;
}
.hpage .subscribe .box_left .left_form dt {
  font-size: 36px;
  font-family: "Grand Hotel", cursive;
  line-height: 1;
}
.hpage .subscribe .box_left .left_form dd {
font-family: 'Tajawal', sans-serif;  font-size: 14px;
}
.hpage .subscribe .form_sub input[type="text"] {
  float: left;
  width: 72.34%;
  border: 1px solid transparent;
  background: #f9fcfa;
  border-radius: 100px 0 0 100px;
  height: 50px;
  padding: 0 20px;
  color: #0567FA;
}
.hpage .subscribe .form_sub input[type="text"]:focus {
  border: 1px solid #0567FA;
  border-right: 1px solid transparent;
}
.hpage .subscribe .form_sub input[type="text"]::-webkit-input-placeholder {
  color: #cccccc;
font-family: 'Tajawal', sans-serif;  font-size: 14px;
}
.hpage .subscribe .form_sub input[type="text"]::-moz-input-placeholder {
  color: #cccccc;
font-family: 'Tajawal', sans-serif;  font-size: 14px;
}
.hpage .subscribe .form_sub input[type="submit"] {
  float: left;
  height: 50px;
  text-align: center;
  line-height: 50px;
  color: #fefefe;
  width: 27.66%;
  background: #0567FA;
  cursor: pointer;
  border: 0;
  text-transform: uppercase;
  border-radius: 0 100px 100px 0;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .subscribe .form_sub input[type="submit"]:hover {
  box-shadow: 0 0 20px 1px rgba(255, 255, 255, 0.5);
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .home_event_gallery {
  background: #ffffff;
  padding-top: 122px;
  padding-bottom: 140px;
}
.hpage .home_event_gallery .title_ {
  text-align: center;
}
.hpage .home_event_gallery .title_ h3 {
  font-size: 48px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  color: #303030;
  margin-bottom: 10px;
}
.hpage .home_event_gallery .title_ h4 {
  font-size: 36px;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  color: #0567FA;
  margin-bottom: 23px;
}
.hpage .home_event_gallery .title_ p {
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  color: #303030;
  line-height: 24px;
}
.hpage .home_event_gallery .box_eg {
  margin-top: 72px;
  position: relative;
  overflow: hidden;
}
.hpage .home_event_gallery .box_eg .shape {
  position: absolute;
  left: 50%;
  top: 50%;
  width: 100px;
  height: 102px;
  margin-left: -50px;
  margin-top: -51px;
  z-index: 5;
  text-align: center;
  line-height: 102px;
}
.hpage .home_event_gallery .box_eg .shape:before {
  content: "\f127";
  font-family: "ionicons";
  font-size: 36px;
  color: #ffffff;
  position: relative;
  z-index: 6;
}
.hpage .home_event_gallery .box_eg .shape .shape_1 {
  position: absolute;
  left: 0;
  top: 0;
  z-index: 1;
}
.hpage .home_event_gallery .box_eg .shape .shape_2 {
  position: absolute;
  left: 7px;
  top: 7px;
  z-index: 2;
}
.hpage .home_event_gallery .item_eg {
  float: left;
  width: 50%;
  padding: 0 40px;
  position: relative;
  overflow: hidden;
}
.hpage .home_event_gallery .item_eg:hover .name_ {
  margin-top: 33px;
}
.hpage .home_event_gallery .item_eg:hover .date_ {
  color: #ffffff;
}
.hpage .home_event_gallery .item_eg:hover .date_:before {
  color: #ffffff;
}
.hpage .home_event_gallery .item_eg:hover .box_img:before {
  background: rgba(60, 187, 134, 0.4);
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .home_event_gallery .item_eg:hover .content {
  margin-top: 21px;
}
.hpage .home_event_gallery .box_img {
  position: absolute;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
}
.hpage .home_event_gallery .box_img:before {
  content: "";
  left: 0;
  bottom: 0;
  right: 0;
  top: 0;
  background: rgba(0, 0, 0, 0.8);
  position: absolute;
}
.hpage .home_event_gallery .box_img img {
  width: 100%;
}
.hpage .home_event_gallery .item_sub {
  position: relative;
  z-index: 2;
  color: #ffffff;
  overflow: hidden;
  height: 280px;
}
.hpage .home_event_gallery .name_ {
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  color: #ffffff;
  font-size: 30px;
  display: block;
  margin-top: 99px;
  white-space: nowrap;
}
.hpage .home_event_gallery .name_:hover {
  text-shadow: 0px 1px 1px rgba(0, 0, 0, 0.5);
}
.hpage .home_event_gallery .date_ {
  float: left;
  width: 100%;
  font-size: 16px;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  color: #aaaaaa;
}
.hpage .home_event_gallery .date_:before {
  content: "\f117";
  font-family: "ionicons";
  line-height: 1;
  color: #0567FA;
  margin-right: 5px;
}
.hpage .home_event_gallery .content {
  float: left;
  width: 100%;
  margin-top: 100%;
}
.hpage .home_event_gallery .content p {
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  line-height: 24px;
}
.hpage .home_event_gallery .content .bt_link {
  color: #ffffff;
font-family: 'Tajawal', sans-serif;  font-size: 14px;
  margin-top: 10px;
  display: block;
}
.hpage .home_event_gallery .content .bt_link:hover:after {
  margin-left: 10px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .home_event_gallery .content .bt_link:after {
  content: "\f10b";
  font-family: "ionicons";
  line-height: 1;
  margin-left: 5px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.hpage .home_maps {
  position: relative;
  overflow: hidden;
  min-height: 572px;
}
.hpage .home_maps .map {
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  right: 0;
}
.hpage .home_maps .map:before {
  content: "";
  left: 0;
  top: 0;
  bottom: 0;
  right: 0;
  position: absolute;
  background: rgba(0, 0, 0, 0.5);
}
.hpage .home_maps .map iframe {
  width: 100%;
  height: 100%;
}
.hpage .home_maps .container {
  position: relative;
  z-index: 5;
}
.hpage .spt .item_spt {
  height: 168px;
  padding: 33px 70px 39px 30px;
  background: #ffffff;
  color: #303030;
  float: left;
  width: 100%;
}
.hpage .spt .item_spt.bg_ {
  background: #0567FA;
  color: #ffffff;
}
.hpage .spt .item_spt.bg_ .icon_ {
  background: #ffffff;
  border-color: #ffd9d9;
  color: #0567FA;
}
.hpage .spt .icon_ {
  float: left;
  width: 15.55%;
  background: #0567FA;
  border: 3px solid #ffd4be;
  border-radius: 50%;
  height: 42px;
  width: 42px;
  text-align: center;
  line-height: 36px;
  font-size: 18px;
  color: #ffffff;
}
.hpage .spt .add_ {
  float: left;
  width: 80.74%;
  margin-left: 3.71%;
}
.hpage .spt .add_ .h3_ {
  font-size: 24px;
  margin-top: 4px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
}
.hpage .spt .add_ dd {
  float: left;
  width: 100%;
  margin: 10px ;
}
.hpage .spt .add_ dt {
  float: left;
  width: 100%;
}
.hpage .spt .add_ dt p {
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  font-size: 14px;
  line-height: 24px;
}
.hpage .spt .add_ dt p:first-child {
  margin-top: -7px;
}
.hpage .loca_ {
  text-align: center;
  padding-top: 126px;
  margin-left: -27px;
}
.hpage .loca_ span {
  display: inline-block;
  color: #ffde00;
  font-size: 18px;
  line-height: 1;
}
.hpage .loca_ .img_ {
  clear: both;
  float: left;
  width: 100%;
  text-align: center;
  margin-top: 1px;
}
.hpage .loca_ .title {
  background: #ffffff;
  border-radius: 3px;
  width: 261px;
  height: 68px;
  float: left;
  padding-top: 14px;
  color: #0567FA;
font-family: 'Tajawal', sans-serif;  position: relative;
  margin-top: 15px;
}
.hpage .loca_ .title:after {
  content: "";
  border-radius: 3px;
  position: absolute;
  left: 1px;
  right: 1px;
  top: 1px;
  bottom: 1px;
  border: 1px solid #6d6c69;
  z-index: 2;
}
.hpage .loca_ .title h4 {
  font-size: 18px;
}
.hpage .loca_ .title p {
  font-size: 14px;
}
.hpage_3 .main_sl .box_sliders:before,
.hpage_4 .main_sl .box_sliders:before {
  content: none;
}
.hpage_3 .main_sl .box_sliders:after,
.hpage_4 .main_sl .box_sliders:after {
  content: none;
}
.category_ {
  background: #f10027;
  min-height: 160px;
  border-top: 5px solid #afe6f1;
  position: relative;
}
.category_ .left_ {
  float: left;
  padding-top: 49px;
}
.category_ .left_ h1{
  font-size: 48px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  color: #ffffff;
}
.category_ .left_ span {
  position: relative;
}
.category_ .left_ span:before {
  content: "";
  position: absolute;
  top: 35px;
  right: -61px;
  width: 49px;
  height: 2px;
  background: #ffffff;
}
.category_ .left_ span:after {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: #ffffff;
  position: absolute;
  top: 31px;
  right: -71px;
  content: "";
}
.category_ .right_ {
  float: right;
  padding-top: 69px;
}
.category_ .right_ .cat_navigation li {
  display: inline-block;
  color: #ffffff;
  margin-right: 10px;
}
.category_ .right_ .cat_navigation li:last-of-type {
  margin-right: 0;
  text-decoration: underline;
  font-style: italic;
}
.category_ .right_ .cat_navigation li a {
  font-size: 14px;
  color: #ffffff;
}
.category_ .right_ .cat_navigation li a:hover {
  text-decoration: underline;
}
.about_welcome .box_welcome {
  border-bottom: 1px solid #f2f2f2;
  min-height: 720px;
  position: relative;
}
.about_welcome .box_welcome:before {
  content: "";
  position: absolute;
  height: 5px;
  width: 100%;
  bottom: -7px;
  background: #f2f2f2;
}
.about_welcome .box_welcome [class*="col-"] {
  position: relative;
  z-index: 5;
}
.about_welcome .title_l {
  padding-top: 145px;
}
.about_welcome .title_l h3 {
  font-weight: 300;
  font-size: 48px;
  color: #303030;
  margin-bottom: 11px;
}
.about_welcome .title_l h4 {
  font-family: "Grand Hotel", cursive;
  font-size: 36px;
  color: #0567FA;
}
.about_welcome .content {
  line-height: 24px;
  color: #303030;
  margin-top: 30px;
}
.about_welcome .content::first-letter {
  font-size: 36px;
  font-weight: 900;
}
.about_welcome .img_ {
  position: absolute;
  right: 0;
  top: 100px;
}
.about_services {
  padding-top: 74px;
  padding-bottom: 87px;
}
.about_services .item_sv {
  text-align: center;
  float: left;
  width: 100%;
}
.about_services .item_sv .box_cl {
  float: left;
  width: 100%;
}
.about_services .item_sv .box_cl:hover .name_ {
  color: #000;
  transition-duration: 0.5s;
  -webkit-transition-duration: 0.5s;
  -moz-transition-duration: 0.5s;
}
.about_services .item_sv .box_cl:hover .icon_:before {
  color: #000;
  transition-duration: 0.5s;
  -webkit-transition-duration: 0.5s;
  -moz-transition-duration: 0.5s;
}
.about_services .item_sv .icon_ {
  float: left;
  text-align: center;
  width: 100%;
  margin-bottom: 25px;
}
.about_services .item_sv .icon_:before {
  font-family: kinder!important;
  color: #0567FA;
  font-size: 66px;
  line-height: 1;
  transition-duration: 0.5s;
  -webkit-transition-duration: 0.5s;
  -moz-transition-duration: 0.5s;
}
.about_services .item_sv .icon_.horse_:before {
  content: "\e904";
}
.about_services .item_sv .icon_.face_:before {
  content: "\e905";
}
.about_services .item_sv .icon_.duck_:before {
  content: "\e906";
}
.about_services .item_sv .name_ {
  font-size: 24px;
  color: #0567FA;
  font-weight: 300;
  transition-duration: 0.5s;
  -webkit-transition-duration: 0.5s;
  -moz-transition-duration: 0.5s;
}
.about_services .item_sv .des_ {
  color: #303030;
  margin-top: 16px;
  float: left;
  line-height: 24px;
}
.about_demo {
  padding-bottom: 140px;
  position: relative;
  z-index: 10;
}
.about_demo .pr_0 {
  padding-right: 0;
}
.about_demo .left_ .top_soc {
  position: relative;
  top: 20px;
}
.about_demo .left_ .top_soc span {
  float: left;
  font-size: 14px;
  color: #777;
  font-style: italic;
}
.about_demo .left_ .top_soc span.line_ {
  height: 1px;
  width: 30px;
  background: #f2722a;
  margin-left: 1px;
  position: relative;
  top: 10px;
  margin-right: 10px;
}
.about_demo .left_ .top_soc span.share_ {
  margin-right: 10px;
}
.about_demo .left_ .top_soc span [class*="ion-"] {
  font-size: 18px;
  margin-left: 11px;
  color: #777;
  position: relative;
  top: -3px;
}
.about_demo .left_ .top_soc span [class*="ion-"]:hover {
  color: #0567FA;
}
.about_demo .left_ .video_ {
  background: url(../images/demo.jpg) no-repeat top left;
  background-size: 100%;
  float: left;
  width: 100%;
  min-height: 450px;
  border-bottom: 10px solid #303030;
  margin-top: 32px;
  position: relative;
  text-align: center;
}
.about_demo .left_ .video_ .box_ {
  position: relative;
  z-index: 2;
  padding-top: 156px;
}
.about_demo .left_ .video_ .box_ .icon_pl {
  border: 0;
  cursor: pointer;
  font-size: 72px;
  line-height: 1;
  color: #ffffff;
  background: none;
  margin-top: -8px;
}
.about_demo .left_ .video_ .box_ .des_ {
  text-transform: uppercase;
  font-weight: 400;
  color: #ffffff;
  margin-top: 9px;
}
.about_demo .left_ .video_:after {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  background: rgba(95, 197, 228, 0.89);
}
.about_demo .pl_0 {
  padding-left: 0;
}
.about_demo .right_ {
  background: #303030;
  border-radius: 30px 30px 30px 0;
  padding: 41px 40px 53px 40px;
  color: #ffffff;
  min-height: 500px;
}
.about_demo .right_ .title_l h3 {
  font-size: 48px;
  font-weight: 300;
  margin-top: -8px;
  margin-bottom: 30px;
}
.about_demo .right_ .title_l h4 {
  color: #f37633;
  font-size: 24px;
  font-family: "Grand Hotel", cursive;
}
.about_demo .right_ .title_l p {
  line-height: 24px;
  margin-top: 14px;
}
.about_demo .right_ .carousel_ {
  margin-top: 27px;
}
.about_demo .right_ .carousel_ .element_ dt {
  width: 42px;
  height: 42px;
  margin-bottom: 19px;
  float: left;
  clear: both;
}
.about_demo .right_ .carousel_ .element_ dt span {
  border-radius: 50%;
  text-align: center;
  line-height: 36px;
  font-weight: 700;
  float: left;
  width: 100%;
  height: 100%;
  background: #0567FA;
  border: 3px solid rgba(248, 183, 148, 0.5);
}
.about_demo .right_ .carousel_ .element_ dd {
  width: 341px;
  float: right;
  display: table-cell;
  vertical-align: middle;
  min-height: 42px;
  line-height: 24px;
}
.about_demo .right_ .carousel_ .element_ dd label {
  line-height: 24px;
  height: 42px;
  display: table-cell;
  vertical-align: middle;
}
.about_demo .right_ .bx-wrapper {
  float: left;
  width: 100%;
}
.about_demo .right_ .bx-wrapper .bx-viewport {
  bottom: 0;
  min-height: 200px;
}
.about_demo .right_ .bx-wrapper .bx-controls {
  left: 0;
  width: 100%;
  text-align: center;
  background: url(../images/shape_demo.png) no-repeat top center;
  height: 5px;
}
.about_demo .right_ .bx-wrapper .bx-controls .bx-pager.bx-default-pager a {
  height: 6px;
  width: 6px;
  line-height: 6px;
  border-radius: 50%;
  background: #ffffff;
  position: relative;
}
.about_demo .right_ .bx-wrapper .bx-controls .bx-pager.bx-default-pager a.active {
  background: none;
}
.about_demo .right_ .bx-wrapper .bx-controls .bx-pager.bx-default-pager a.active:before {
  content: "";
  width: 10px;
  height: 10px;
  border: 1px solid #e86c29;
  position: absolute;
  left: 0;
  top: -2px;
  border-radius: 50%;
}
.video-target {
  cursor: pointer;
}
.video-wrapper {
  display: none;
  position: fixed;
  min-width: 100%;
  min-height: 100%;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: #000;
  z-index: 21000;
}
.video-frame {
  position: absolute;
  top: 50%;
  left: 50%;
}
.video-close {
  float: right;
  margin-top: -30px;
  margin-right: -30px;
  cursor: pointer;
  color: #fff;
  border: 1px solid #AEAEAE;
  border-radius: 30px;
  background: #605F61;
  font-size: 31px;
  font-weight: bold;
  display: inline-block;
  line-height: 0px;
  padding: 11px 3px;
}
.about_build {
  background: #ffffff;
  padding-top: 140px;
}
.about_build .left_ .title_l h3 {
  font-weight: 300;
  font-size: 48px;
  color: #303030;
  margin-top: -8px;
  margin-bottom: 11px;
}
.about_build .left_ .title_l h4 {
  font-size: 36px;
  font-family: "Grand Hotel", cursive;
  color: #0567FA;
}
.about_build .left_ .title_l p {
  line-height: 24px;
  margin-top: 22px;
}
.about_build .right_ .item_cter {
  float: left;
  width: 48.05%;
  margin-right: 3.9%;
  background: #5fc5e4;
  height: 120px;
  border-radius: 20px;
  position: relative;
  color: #ffffff;
  margin-bottom: 30px;
  overflow: hidden;
}
.about_build .right_ .item_cter:hover img {
  right: 10px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.about_build .right_ .item_cter:hover img.chicken {
  right: -15px;
}
.about_build .right_ .item_cter:hover img.cter3 {
  right: -15px;
}
.about_build .right_ .item_cter:hover img.dino {
  right: -15px;
}
.about_build .right_ .item_cter b {
  font-size: 48px;
  position: absolute;
  top: 23px;
  left: 30px;
}
.about_build .right_ .item_cter b.sub:after {
  content: "+";
  font-size: 25px;
  font-weight: normal;
  position: relative;
  top: -17px;
}
.about_build .right_ .item_cter p {
  font-style: italic;
  text-transform: uppercase;
  position: absolute;
  bottom: 31px;
  left: 30px;
}
.about_build .right_ .item_cter img {
  position: absolute;
  bottom: -15px;
  right: -5px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.about_build .right_ .item_cter img.chicken {
  bottom: -31px;
  right: -30px;
}
.about_build .right_ .item_cter img.cter3 {
  bottom: -10px;
  right: -30px;
}
.about_build .right_ .item_cter img.dino {
  bottom: -25px;
  right: -30px;
}
.about_build .right_ .item_cter:nth-child(2n) {
  margin-right: 0;
}
.about_donate {
  background: #ffffff;
  min-height: 466px;
  padding-top: 90px;
  padding-bottom: 50px;
}
.about_donate .title_ {
  text-align: center;
}
.about_donate .title_ h3 {
  font-size: 48px;
  color: #303030;
  font-weight: 300;
  margin-top: -8px;
}
.about_donate .title_ p {
  line-height: 24px;
  margin-top: 25px;
  margin-bottom: 32px;
}
.about_donate .title_ .btn_donate {
  width: 260px;
  height: 50px;
  border-radius: 100px;
  background: #0567FA;
  color: #ffffff;
  font-weight: 900;
  text-transform: uppercase;
  text-align: center;
  line-height: 50px;
  display: block;
  margin: 0 auto;
  border: 1px solid transparent;
}
.about_donate .title_ .btn_donate:hover {
  background: #ffffff;
  color: #0567FA;
  border: 1px solid #0567FA;
}
.page_about ._section_featured {
  margin-top: 140px;
}
.about_pl_grow {
  height: 682px;
  background: #60c0cc;
  position: relative;
}
.about_pl_grow:before {
  content: "";
  position: absolute;
  left: 0;
  top: -51px;
  height: 51px;
  width: 100%;
  background: url(../images/shape_about.png) top left repeat-x;
}
.about_pl_grow .title_ {
  text-align: center;
  color: #ffffff;
  font-size: 72px;
  font-weight: 300;
  position: relative;
  z-index: 2;
  top: 4px;
}
.about_pl_grow .title_ span {
  font-size: 120px;
}
.about_pl_grow .pl_item {
  color: #ffffff;
  float: left;
  width: 100%;
  padding-bottom: 40px;
  margin-top: 66px;
}
.about_pl_grow .pl_item dt {
  float: left;
  width: 18.91%;
}
.about_pl_grow .pl_item dt h3 {
  font-family: "Grand Hotel", cursive;
  font-size: 64px;
}
.about_pl_grow .pl_item.sub {
  margin-top: 0;
}
.about_pl_grow .pl_item.sub dd {
  float: right;
  width: 72.97%;
}
.about_pl_grow .pl_item dd {
  float: left;
  width: 81.09%;
}
.about_pl_grow .pl_item dd h3 {
  font-weight: 700;
  font-size: 18px;
}
.about_pl_grow .pl_item dd p {
  line-height: 22px;
  margin-top: 19px;
}
.about_pl_grow .pl_item dd span {
  background: url(../images/shape_grow.png) no-repeat left top;
  display: block;
  width: 100%;
  height: 6px;
  margin-top: 24px;
}
.about_pl_grow .item_midde {
  float: left;
  position: relative;
  z-index: 1;
  top: -227px;
  width: 100%;
  text-align: center;
}
.about_pl_grow .pl_grow_video {
  top: -228px;
  position: relative;
}
.classes_enroll {
  padding-bottom: 220px;
}
.classes_enroll .top_enroll {
  height: 201px;
  border-bottom: 5px solid #eeeeee;
}
.classes_enroll .top_enroll .left_ {
  float: left;
  margin-top: 140px;
}
.classes_enroll .top_enroll .left_ h1{
  font-size: 36px;
  margin-top: -6px;
  font-weight: 400;
}
.classes_enroll .top_enroll .left_ h1span {
  font-weight: 300;
}
.classes_enroll .top_enroll .right_ {
  float: right;
}
.classes_enroll .top_enroll .right_ .spt {
  float: left;
  text-align: right;
  margin-top: 125px;
  margin-right: 13px;
}
.classes_enroll .top_enroll .right_ .spt dt {
  color: #777;
  margin-bottom: 5px;
}
.classes_enroll .top_enroll .right_ .spt dt span {
  color: #0567FA;
}
.classes_enroll .top_enroll .right_ .spt dd {
  font-size: 24px;
  color: #0567FA;
  font-weight: 700;
}
.classes_enroll .top_enroll .right_ .bub {
  float: right;
  height: 106px;
  margin-top: 70px;
  width: 100px;
  background: url(../images/bub.png);
  text-align: center;
  line-height: 106px;
}
.classes_enroll .top_enroll .right_ .bub span {
  font-size: 16px;
  font-weight: 900;
  color: #ffffff;
}
.classes_enroll .title_sort {
  height: 107px;
}
.classes_enroll .title_sort .left_ {
  float: left;
}
.classes_enroll .title_sort .left_ span {
  color: #777777;
  float: left;
  margin-top: 15px;
}
.classes_enroll .title_sort .right_ {
  float: right;
}
.classes_enroll .title_sort .right_ .view_style {
  float: left;
  margin-top: 21px;
}
.classes_enroll .title_sort .right_ .view_style li {
  float: left;
  color: #777777;
  margin-left: 8px;
}
.classes_enroll .title_sort .right_ .view_style li a {
  color: #cccccc;
  font-size: 18px;
  position: relative;
  top: -3px;
}
.classes_enroll .title_sort .right_ .view_style li a.atv {
  color: #303030;
}
.classes_enroll .item_ .classes_it {
  margin-bottom: 30px;
  border-radius: 20px;
  border-right-color: transparent;
  transition-duration: 0.4s;
  -webkit-transition-duration: 0.4s;
  -moz-transition-duration: 0.4s;
}
.classes_enroll .item_ .classes_it:hover {
  -webkit-box-shadow: 0px 0px 7px 0px rgba(0, 0, 0, 0.1);
  -moz-box-shadow: 0px 0px 7px 0px rgba(0, 0, 0, 0.1);
  box-shadow: 0px 0px 7px 0px rgba(0, 0, 0, 0.1);
  border-right-color: transparent;
  transition-duration: 0.4s;
  -webkit-transition-duration: 0.4s;
  -moz-transition-duration: 0.4s;
}
.classes_enroll .item_ .classes_it:hover .box_suma {
  background: #f8f8f8;
  border-left-color: transparent;
}
.classes_enroll .item_ .classes_it:hover .box_img .wave:before {
  background-image: radial-gradient(circle at 10px -5px, transparent 14px, #f8f8f8 16px);
}
.classes_enroll .item_ .classes_it:hover .box_img .wave:after {
  background-image: radial-gradient(circle at 10px 15px, #f8f8f8 12px, transparent 13px);
}
.classes_enroll .item_ .classes_it .box_img {
  position: relative;
  width: 100%;
  overflow: hidden;
  z-index: 2;
  border-radius: 20px 20px 0 0;
}
.classes_enroll .item_ .classes_it .box_img:hover img {
  transform: scale(1);
  opacity: 0.75;
  -webkit-transform: scale(1);
  -moz-transform: scale(1);
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.classes_enroll .item_ .classes_it .box_img img {
  transform: scale(1.1);
  -webkit-transform: scale(1.1);
  -moz-transform: scale(1.1);
  border-radius: 15px 15px 0 0;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
  width: 100%;
}
.classes_enroll .item_ .classes_it .box_img .wave {
  position: absolute;
  width: 100%;
  left: 0;
  bottom: 0;
  height: 0;
}
.classes_enroll .item_ .classes_it .box_img .wave:before {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  right: 0;
  background-repeat: repeat;
  height: 12px;
  background-size: 20px 20px;
  background-image: radial-gradient(circle at 10px -5px, transparent 14px, #ffffff 16px);
}
.classes_enroll .item_ .classes_it .box_img .wave:after {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  right: 0;
  background-repeat: repeat;
  height: 12px;
  background-size: 40px 20px;
  background-image: radial-gradient(circle at 10px 15px, #ffffff 12px, transparent 13px);
}
.classes_enroll .item_ .classes_it .box_suma {
  border: 1px solid #eeeeee;
  border-top: 0;
  height: 349px;
  margin-top: -15px;
  padding: 30px 30px 39px 30px;
  border-radius: 0 0 20px 20px;
  position: relative;
  background: #ffffff;
}
.classes_enroll .item_ .classes_it .box_suma .date_ {
  margin-bottom: 7px;
}
.classes_enroll .item_ .classes_it .box_suma .date_ span {
  float: left;
  font-size: 18px;
  font-family: "Grand Hotel", cursive;
  color: #777;
  margin-right: 20px;
}
.classes_enroll .item_ .classes_it .box_suma .name_ {
  font-size: 30px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  line-height: 1;
  color: #303030;
  white-space: nowrap;
}
.classes_enroll .item_ .classes_it .box_suma .rate_ {
  margin-top: 15px;
}
.classes_enroll .item_ .classes_it .box_suma .rate_ span {
  color: #0567FA;
  font-size: 18px;
}
.classes_enroll .item_ .classes_it .box_suma .sumary_ {
  margin-top: 10px;
}
.classes_enroll .item_ .classes_it .box_suma .sumary_ p {
  font-size: 14px;
  color: #303030;
  line-height: 24px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
}
.classes_enroll .item_ .classes_it .box_suma .btn_apply {
  text-transform: uppercase;
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  color: #ffffff;
  background: #0567FA;
  width: 144px;
  height: 40px;
  line-height: 40px;
  position: absolute;
  left: 30px;
  bottom: 39px;
  text-align: center;
  border-radius: 20px;
  text-indent: -13px;
  overflow: hidden;
}
.classes_enroll .item_ .classes_it .box_suma .btn_apply:before {
  right: 10px;
  opacity: 0;
  font-family: "ionicons";
  position: relative;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
  content: "\f38e";
}
.classes_enroll .item_ .classes_it .box_suma .btn_apply:hover {
  background: #cc591c;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
  text-indent: 7.5px;
}
.classes_enroll .item_ .classes_it .box_suma .btn_apply:hover:before {
  content: "\f38e";
  right: 7px;
  opacity: 1;
  font-family: "ionicons";
  position: relative;
}
.classes_enroll .item_ .classes_it .box_suma .more_ {
  position: absolute;
  right: 30px;
  bottom: 46.5px;
  height: 25px;
  width: 25px;
  border: 0;
  background: transparent;
  cursor: pointer;
  display: block;
  overflow: hidden;
  padding: 0;
}
.classes_enroll .item_ .classes_it .box_suma .more_:active span {
  background: #0567FA;
}
.classes_enroll .item_ .classes_it .box_suma .more_:hover span {
  background: #0567FA;
}
.classes_enroll .item_ .classes_it .box_suma .more_:hover + .popup_ {
  opacity: 1;
}
.classes_enroll .item_ .classes_it .box_suma .more_ span {
  width: 5px;
  height: 5px;
  border-radius: 50%;
  display: inline-block;
  background: #cccccc;
}
.classes_enroll .item_ .classes_it .box_suma .popup_ {
  position: absolute;
  right: 3px;
  bottom: 15px;
  border-radius: 20px;
  text-align: center;
  display: block;
  width: 78px;
  height: 28px;
  border: 1px solid #aaaaaa;
  line-height: 26px;
  opacity: 0;
}
.classes_enroll .item_ .classes_it .box_suma .popup_ .btn_popup {
  font-size: 12px;
  color: #777;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
}
.classes_enroll .item_ .classes_it .box_suma .popup_:hover {
  opacity: 1;
}
.classes_enroll .item_ .classes_it .box_suma .popup_:after,
.classes_enroll .item_ .classes_it .box_suma .popup_:before {
  bottom: 100%;
  left: 50%;
  border: solid transparent;
  content: " ";
  height: 0;
  width: 0;
  position: absolute;
  pointer-events: none;
}
.classes_enroll .item_ .classes_it .box_suma .popup_:after {
  border-color: rgba(250, 250, 250, 0);
  border-bottom-color: #fafafa;
  border-width: 7.5px;
  margin-left: -7.5px;
}
.classes_enroll .item_ .classes_it .box_suma .popup_:before {
  border-color: rgba(170, 170, 170, 0);
  border-bottom-color: #aaaaaa;
  border-width: 8.5px;
  margin-left: -8.5px;
}
.classes_enroll .navigation {
  float: right;
  margin-top: 50px;
}
.classes_enroll .navigation li {
  height: 36px;
  width: 36px;
  float: left;
  text-align: center;
  line-height: 36px;
  margin-left: 10px;
}
.classes_enroll .navigation li a {
  border: 1px solid #aaaaaa;
  color: #777777;
  border-radius: 3px;
  float: left;
  width: 100%;
  height: 100%;
}
.classes_enroll .navigation li a:hover {
  border-color: #0567FA;
}
.classes_enroll .navigation li a.natv {
  border-color: transparent;
  color: #ffffff;
  background: #0567FA;
  border-bottom: 3px solid #da5c18;
  cursor: default;
}
.page_class_single {
  padding-top: 80px;
  padding-bottom: 220px;
}
.page_class_single .leftview .letter {
  position: relative;
  border-top: 5px solid #f6f6f6;
  padding-top: 41px;
}
.page_class_single .leftview .letter .shape_lt {
  position: absolute;
  top: 17px;
  right: 0;
  width: 120px;
  height: 80px;
  text-align: center;
  line-height: 80px;
  background: url(../images/letter.png) no-repeat top center;
}
.page_class_single .leftview .letter .shape_lt span {
  font-family: "Grand Hotel", cursive;
  font-size: 24px;
  color: #ffffff;
}
.page_class_single .leftview .letter .name_ {
  margin-top: -8px;
  float: left;
  width: 100%;
}
.page_class_single .leftview .letter .name_ h3 {
  font-size: 48px;
  font-weight: 300;
}
.page_class_single .leftview .letter .rate_ {
  float: left;
  width: 100%;
  margin-top: 12px;
}
.page_class_single .leftview .letter .rate_ span {
  font-size: 18px;
  color: #0567FA;
}
.page_class_single .leftview .letter .key_ {
  float: left;
  width: 100%;
  margin-top: 15px;
}
.page_class_single .leftview .letter .key_ li {
  float: left;
  margin-right: 3px;
  color: #cccccc;
}
.page_class_single .leftview .letter .key_ li:nth-child(2) a {
  color: #0567FA;
}
.page_class_single .leftview .letter .key_ li:nth-child(2) a:hover {
  color: #ccc;
}
.page_class_single .leftview .letter .key_ li a {
  color: #cccccc;
  text-transform: uppercase;
}
.page_class_single .leftview .letter .key_ li a:hover {
  color: #0567FA;
}
.page_class_single .leftview .letter .btn_enroll {
  width: 265px;
  height: 50px;
  border-radius: 25px;
  float: left;
  border: 1px solid #0567FA;
  font-size: 16px;
  font-weight: 700;
  color: #0567FA;
  text-align: center;
  line-height: 50px;
  margin-top: 27px;
}
.page_class_single .leftview .letter .btn_enroll:hover {
  background: #0567FA;
  color: #ffffff;
  transition-duration: 0.5s;
}
.page_class_single .leftview .letter .btn_enroll:before {
  content: "\f38e";
  font-family: "ionicons";
  margin-right: 10px;
  font-size: 18px;
}
.page_class_single .leftview .letter .content {
  float: left;
  width: 100%;
  margin-top: 29px;
}
.page_class_single .leftview .letter .content > p {
  line-height: 24px;
  color: #777777;
}
.page_class_single .leftview .letter .content b {
  color: #0567FA;
}
.page_class_single .leftview .letter .content i {
  text-decoration: underline;
}
.page_class_single .leftview .letter .content .quote {
  margin: 35px 0;
  float: left;
  width: 100%;
  height: 165px;
  border: 1px solid #f6f6f6;
  border-left: 10px solid #56b2cf;
  padding-left: 60px;
  padding-top: 40px;
  padding-right: 140px;
  background: #ffffff url(../images/quote.png) no-repeat top 42px right 59px;
}
.page_class_single .leftview .letter .content .quote h3 {
  font-size: 24px;
  font-weight: 900;
  font-style: italic;
  color: #777;
  margin-bottom: 8px;
}
.page_class_single .leftview .letter .content .quote p {
  font-weight: 700;
  font-style: italic;
  color: #777;
  line-height: 26px;
}
.page_class_single .leftview .questions .title_ {
  font-size: 24px;
  font-weight: 300;
  margin-bottom: 34px;
  margin-top: 20px;
}
.page_class_single .leftview .questions .accordion {
  float: left;
  width: 100%;
}
.page_class_single .sidebar .popular {
  height: 472px;
  background: #0567FA;
  border-radius: 20px;
  padding: 10px;
  margin-bottom: 72px;
}
.page_class_single .sidebar .popular .box {
  color: #ffffff;
  border: 3px dotted #f69a6a;
  height: 100%;
  border-radius: 20px;
  padding: 14px 30px;
}
.page_class_single .sidebar .popular .box li {
  font-family: "Grand Hotel", cursive;
  font-size: 24px;
  height: 84px;
  line-height: 84px;
}
.page_class_single .sidebar .popular .box li:first-child {
  border-top: 0!important;
}
.page_class_single .sidebar .popular .box li:last-child {
  border-bottom: 0!important;
}
.page_class_single .sidebar .popular .box li:nth-child(odd) {
  border-bottom: 1px solid #ea6a25;
  border-top: 1px solid #f67936;
}
.page_class_single .sidebar .popular .box li:nth-child(even) {
  border-top: 1px solid #f67936;
  border-bottom: 1px solid #ea6a25;
}
.page_class_single .sidebar .popular .box li span {
  margin-right: 10px;
  position: relative;
}
.page_class_single .sidebar .popular .box li b {
  margin-left: 8px;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  font-size: 30px;
}
.page_class_single .sidebar .popular .box li sup {
  font-size: 12px;
  font-style: italic;
  font-weight: 400;
  bottom: 16px;
}
.page_class_single .sidebar .nav_ {
  float: left;
  width: 100%;
  position: relative;
}
.page_class_single .sidebar .nav_.first_ {
  margin-bottom: 7px;
}
.page_class_single .sidebar .nav_.dot_ {
  margin-bottom: 19px;
}
.page_class_single .sidebar .nav_.dot_:before {
  position: absolute;
  content: "";
  height: 1px;
  width: 60px;
  background: #f1f1f1;
  bottom: -19px;
  left: 0;
}
.page_class_single .sidebar .nav_ a {
  color: #303030;
  font-size: 36px;
  font-weight: 300;
  margin-top: -6px;
  margin-left: -4px;
}
.page_class_single .sidebar .sum {
  float: left;
  width: 100%;
  color: #9f9f9f;
  margin-top: 10px;
}
.page_class_single .sidebar .sum b {
  font-weight: 700;
  font-style: italic;
}
.page_class_single .sidebar .box_img {
  margin-top: 47px;
  margin-bottom: 25px;
  float: left;
  width: 100%;
  height: 181px;
  overflow: hidden;
  border-radius: 20px;
  position: relative;
  transition-duration: 0.2s;
}
.page_class_single .sidebar .box_img:hover {
  transition-duration: 0.2s;
  border-radius: 0;
  border-bottom: 5px solid #0567FA;
}
.page_class_single .sidebar .box_img img {
  width: 100%;
}
.page_class_single .classes_related {
  border-top: 5px solid #f1f1f1;
  margin-top: 80px;
  padding-top: 66px;
}
.page_class_single .classes_related .name_ {
  float: left;
  width: 100%;
}
.page_class_single .classes_related .name_ h3 {
  font-size: 36px;
  font-weight: 300;
}
.page_class_single .classes_related .box_pro {
  margin-top: 36px;
}
.page_class_single .classes_related .box_pro .item_pro {
  float: left;
  width: 23.077%;
  margin-right: 2.564%;
}
.page_class_single .classes_related .box_pro .item_pro:nth-child(4n) {
  margin-right: 0;
}
.page_class_single .classes_related .box_pro .box_img {
  position: relative;
  width: 100%;
  height: 180px;
  border-radius: 20px;
  overflow: hidden;
}
.page_class_single .classes_related .box_pro .box_img:hover .pro_img {
  opacity: 0.8;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.page_class_single .classes_related .box_pro .box_img:hover .overlay {
  position: absolute;
  background: rgba(242, 111, 41, 0.5);
  left: 5px;
  top: 5px;
  right: 5px;
  bottom: 5px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.page_class_single .classes_related .box_pro .box_img:hover .overlay a {
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
  top: 50%;
  opacity: 1;
}
.page_class_single .classes_related .box_pro .box_img .pro_img {
  width: 100%;
  border-radius: 20px;
}
.page_class_single .classes_related .box_pro .nav_ {
  float: left;
  width: 100%;
  position: relative;
  margin-top: 17px;
}
.page_class_single .classes_related .box_pro .nav_.first_ {
  margin-bottom: 7px;
}
.page_class_single .classes_related .box_pro .nav_.dot_ {
  margin-bottom: 19px;
}
.page_class_single .classes_related .box_pro .nav_.dot_:before {
  position: absolute;
  content: "";
  height: 1px;
  width: 60px;
  background: #f1f1f1;
  bottom: -19px;
  left: 0;
}
.page_class_single .classes_related .box_pro .nav_ a {
  color: #303030;
  font-size: 24px;
  font-weight: 300;
  margin-top: -6px;
  margin-left: -4px;
}
.page_class_single .classes_related .box_pro .sum {
  float: left;
  width: 100%;
  color: #9f9f9f;
  margin-top: 10px;
}
.page_class_single .classes_related .box_pro .sum b {
  font-weight: 700;
  font-style: italic;
}
.page_class_single .classes_related .box_pro .overlay {
  position: absolute;
  border-radius: 20px;
  left: 50%;
  top: 50%;
  right: 50%;
  bottom: 50%;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.page_class_single .classes_related .box_pro .overlay a {
  position: absolute;
  margin-top: -15px;
  margin-left: -15px;
  left: 50%;
  top: -100%;
  opacity: 0;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.page_class_single .leftview_2 .letter .btn_enroll_r {
  position: absolute;
  text-transform: uppercase;
  color: #0567FA;
  font-size: 16px;
  font-weight: 700;
  right: 0;
  top: 131px;
}
.page_class_single .leftview_2 .letter .btn_enroll_r:hover {
  color: #303030;
}
.page_class_single .leftview_2 .letter .btn_enroll_r:after {
  content: "\f3d6";
  font-family: "ionicons";
  font-size: 24px;
  line-height: 1;
  top: 3px;
  position: relative;
  margin-left: 9px;
}
.page_class_single .leftview_2 .letter .content {
  width: 48.05%;
  margin-top: 48px;
}
.page_class_single .leftview_2 .letter .content .quote {
  height: inherit;
  min-height: 168px;
  padding-bottom: 20px;
  padding-right: 10px;
  padding-top: 23px;
  background: #ffffff;
  position: relative;
}
.page_class_single .leftview_2 .letter .content .quote img {
  position: absolute;
  right: 13px;
  bottom: -17px;
}
.page_class_single .leftview_2 .letter .content .quote h3 {
  white-space: pre-line;
  line-height: 30px;
}
.page_class_single .leftview_2 .letter .content_r {
  width: 48.05%;
  float: right;
  margin-top: 54px;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ {
  padding-top: 33px;
  float: left;
  width: 100%;
  border: 1px solid #eeeeee;
  border-radius: 3px;
  background: #f8f8f8;
  height: 181px;
  margin-bottom: 30px;
  position: relative;
  overflow: hidden;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_:hover {
  background: rgba(0, 0, 0, 0.9);
  transition-duration: 0.5s;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_:hover .cont_ a {
  color: #ffffff;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_:hover .cont_ p {
  color: #838383;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .box_img {
  position: absolute;
  z-index: -1;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .box_img img {
  width: 100%;
  height: 100%;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .icon_ {
  font-size: 72px;
  color: #0567FA;
  line-height: 1;
  float: left;
  width: 23.24%;
  text-align: center;
  display: block;
  margin-top: -5px;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .icon_ .ion-ios-musical-note {
  position: relative;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .icon_ .ion-ios-musical-note:after {
  position: absolute;
  right: -3px;
  content: "\f46b";
  font-family: "ionicons";
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .cont_ {
  float: left;
  width: 76.76%;
  padding-right: 30px;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .cont_ a {
  font-size: 24px;
  color: #303030;
  font-weight: 300;
  float: left;
  margin-top: -4px;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .cont_ a:hover {
  color: #0567FA;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .cont_ dl {
  float: left;
  width: 100%;
  margin-top: 9px;
  margin-bottom: 16px;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .cont_ dl dt {
  float: left;
  color: #0567FA;
  font-size: 18px;
  font-family: "Grand Hotel", cursive;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .cont_ dl dd {
  float: left;
  margin-left: 22px;
  padding-top: 2px;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .cont_ dl dd span {
  color: #f9ce3a;
  float: left;
  margin-right: 1px;
}
.page_class_single .leftview_2 .letter .content_r .box_rate_ .cont_ p {
  line-height: 24px;
  float: left;
}
.page_gallery {
  padding-bottom: 220px;
}
.page_gallery ._section_gallery {
  padding-bottom: 30px;
}
.page_gallery .view_bot {
  padding-top: 30px;
  border-top: 5px solid #f7f7f7;
}
.page_gallery .view_bot .navigation {
  float: left;
}
.page_gallery .view_bot .navigation li {
  height: 36px;
  width: 36px;
  float: left;
  text-align: center;
  line-height: 36px;
  margin-left: 10px;
}
.page_gallery .view_bot .navigation li a {
  border: 1px solid #aaaaaa;
  color: #777777;
  border-radius: 3px;
  float: left;
  width: 100%;
  height: 100%;
}
.page_gallery .view_bot .navigation li a:hover {
  border-color: #0567FA;
}
.page_gallery .view_bot .navigation li a.natv {
  border-color: transparent;
  color: #ffffff;
  background: #0567FA;
  border-bottom: 3px solid #da5c18;
  cursor: default;
}
.page_gallery .view_bot .view_style {
  float: right;
}
.page_gallery .view_bot .view_style li {
  float: left;
  color: #777777;
  margin-left: 8px;
}
.page_gallery .view_bot .view_style li a {
  color: #cccccc;
  font-size: 18px;
  position: relative;
  top: -3px;
}
.page_gallery .view_bot .view_style li a.atv {
  color: #303030;
}
.page_404 .oops {
  margin-bottom: 349px;
  float: left;
  margin-top: 260px;
}
.page_404 .oops h3 {
  font-size: 72px;
  font-weight: 300;
  margin-top: -13px;
  margin-bottom: 12px;
}
.page_404 .oops h4 {
  font-size: 36px;
  font-weight: 300;
  margin-bottom: 26px;
}
.page_404 .oops p {
  color: #777;
  line-height: 24px;
}
.page_404 .oops .btn {
  text-transform: uppercase;
  color: #f2702a;
  width: 270px;
  height: 50px;
  text-align: center;
  line-height: 48px;
  background: #ffffff;
  border-radius: 25px;
  border: 1px solid #0567FA;
  display: block;
  font-weight: 700;
  margin-top: 42px;
  transition-duration: 0.4s;
}
.page_404 .oops .btn:hover {
  background: #0567FA;
  color: #ffffff;
  transition-duration: 0.4s;
}
.page_404 .box_img {
  float: left;
  width: 100%;
  position: relative;
  top: 145px;
  right: 20px;
}
.comingsoon {
  height: 940px;
  background: url(../images/cms.jpg) no-repeat top center;
  background-size: 100% 940px;
  position: relative;
  padding-top: 40px;
  text-align: center;
  color: #ffffff;
}
.comingsoon:before {
  content: "";
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  background: rgba(0, 0, 0, 0.7);
  position: absolute;
}
.comingsoon .container {
  position: relative;
  z-index: 2;
}
.comingsoon .lg {
  float: left;
}
.comingsoon .lg img {
  width: 170px;
}
.comingsoon .title_ {
  float: left;
  width: 100%;
  margin-top: 63px;
}
.comingsoon .title_ h3 {
  font-size: 60px;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  margin-bottom: 21px;
}
.comingsoon .title_ p {
  line-height: 24px;
}
.comingsoon .box_cd {
  float: left;
  width: 100%;
  margin-top: 93px;
  margin-bottom: 100px;
}
.comingsoon .box_cd #countdown li {
  margin: 0 49.5px;
  display: inline-block;
  width: 160px;
  height: 160px;
  background: url(../images/moon.png) no-repeat top center;
}
.comingsoon .box_cd #countdown li span {
  color: #ffffff;
  font-size: 50px;
  font-weight: 300;
font-family: 'Tajawal', sans-serif;  display: block;
  margin-top: 41px;
  margin-bottom: 34px;
}
.comingsoon .box_cd #countdown li p {
  font-size: 24px;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  color: #303030;
}
.comingsoon .form_ {
  width: 440px;
  text-align: center;
  margin: 0 auto;
  display: block;
}
.comingsoon .form_ .sub input[type="text"] {
  float: left;
  height: 50px;
  width: 75.682%;
  border: 1px solid #563320;
  background: transparent;
  border-radius: 3px 0 0 3px;
  padding: 0 20px;
  color: #ffffff;
  font-weight: 300;
}
.comingsoon .form_ .sub input[type="text"]:focus {
  border-color: #0567FA;
  font-weight: 300;
}
.comingsoon .form_ .sub input[type="text"]:focus::-webkit-input-placeholder {
  color: #ffffff;
}
.comingsoon .form_ .sub input[type="text"]:focus::-moz-input-placeholder {
  color: #ffffff;
}
.comingsoon .form_ .sub input[type="text"]:focus + input[type="submit"] {
  border-color: #0567FA;
  color: #0567FA;
}
.comingsoon .form_ .sub input[type="text"]::-webkit-input-placeholder {
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  color: #534239;
}
.comingsoon .form_ .sub input[type="text"]::-moz-input-placeholder {
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  color: #534239;
}
.comingsoon .form_ .sub input[type="submit"] {
  float: left;
  height: 50px;
  width: 24.318%;
  border: 1px solid #563320;
  background: transparent;
  border-left: 0;
  cursor: pointer;
  font-weight: 300;
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  color: #534239;
  border-radius: 0 3px 3px 0;
}
.comingsoon .social_ {
  float: left;
  width: 100%;
  margin-top: 20px;
}
.comingsoon .social_ li {
  display: inline-block;
  margin: 0 4.5px;
}
.comingsoon .social_ li a {
  font-size: 18px;
  line-height: 1;
  color: #554239;
  width: 40px;
  height: 40px;
  display: block;
  border-radius: 50%;
  text-align: center;
  line-height: 38px;
  border: 1px solid #554239;
  transition-duration: 0.5s;
}
.comingsoon .social_ li a.ion-social-facebook {
  border-color: #0567FA;
  background: #0567FA;
  color: #ffffff;
}
.comingsoon .social_ li a:hover {
  border-color: #0567FA;
  background: #0567FA;
  color: #ffffff;
  transition-duration: 0.5s;
}
.contact_hd:after {
  content: "";
  height: 5px;
  width: 100%;
  background: rgba(86, 178, 207, 0.3);
  z-index: 2;
  bottom: -5px;
  left: 0;
  position: absolute;
}
.contact_page {
  padding-bottom: 220px;
}
.contact_page .maps {
  height: 500px;
  position: relative;
  margin-bottom: 80px;
}
.contact_page .maps:before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  background: rgba(86, 178, 207, 0.3);
}
.contact_page .maps .point {
  position: absolute;
  left: 50%;
  margin-left: -24px;
  top: 213px;
  background: url(../images/point.png) no-repeat top center;
  width: 48px;
  height: 70px;
  text-align: center;
}
.contact_page .maps .point:hover span {
  color: #303030;
  transition-duration: 0.4s;
}
.contact_page .maps .point span {
  transition-duration: 0.4s;
  color: #ffffff;
  font-size: 24px;
  display: block;
  margin-top: 14px;
  margin-left: -2px;
}
.contact_page .maps iframe {
  float: left;
  width: 100%;
  height: 500px;
}
.contact_page .box_mes .title_l {
  float: left;
  width: 100%;
  margin-top: -8px;
}
.contact_page .box_mes .title_l h3 {
  font-size: 48px;
  font-weight: 300;
  margin-bottom: 10px;
}
.contact_page .box_mes .title_l h4 {
  font-weight: 400;
  font-family: "Grand Hotel", cursive;
  color: #0567FA;
  font-size: 36px;
  margin-bottom: 28px;
}
.contact_page .box_mes .title_l p {
  line-height: 24px;
}
.contact_page .box_mes .form_ {
  float: left;
  width: 100%;
  margin-top: 53px;
}
.contact_page .box_mes .form_ .required {
  position: relative;
  float: left;
  width: 48.05%;
}
.contact_page .box_mes .form_ .required.first {
  margin-right: 3.9%;
}
.contact_page .box_mes .form_ .required:before {
  content: "*";
  color: #f10027;
  position: absolute;
  top: 17px;
  left: 20px;
}
.contact_page .box_mes .form_ input[type="text"] {
  height: 49px;
  border-radius: 50px;
  margin-bottom: 20px;
  border: 1px solid #eeeeee;
  padding: 0 28px;
}
.contact_page .box_mes .form_ input[type="text"]:focus {
  border: 1px solid #0567FA;
  transition-duration: 0.4s;
}
.contact_page .box_mes .form_ input[type="text"]::-webkit-input-placeholder {
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #303030;
  font-size: 14px;
}
.contact_page .box_mes .form_ input[type="text"]::-moz-placeholder {
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #303030;
  font-size: 14px;
}
.contact_page .box_mes .form_ textarea {
  padding: 16px 19px;
  float: left;
  width: 100%;
  resize: none;
  margin-bottom: 20px;
  height: 211px;
  border-radius: 20px;
  border: 1px solid #eeeeee;
}
.contact_page .box_mes .form_ textarea:focus {
  border: 1px solid #0567FA;
  transition-duration: 0.4s;
}
.contact_page .box_mes .form_ textarea::-webkit-input-placeholder {
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #303030;
  font-size: 14px;
}
.contact_page .box_mes .form_ textarea::-moz-placeholder {
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #303030;
  font-size: 14px;
}
.contact_page .box_mes .form_ input[type="submit"] {
  width: 48.052%;
  float: left;
  border-radius: 50px;
  height: 49px;
  text-align: center;
  line-height: 49px;
  text-transform: uppercase;
  color: #ffffff;
  font-weight: 700;
  cursor: pointer;
  border: 0;
  background: #0567FA;
font-family: 'Tajawal', sans-serif;  transition-duration: 0.4s;
  border: 1px solid transparent;
}
.contact_page .box_mes .form_ input[type="submit"]:hover {
  color: #0567FA;
  border: 1px solid #0567FA;
  transition-duration: 0.4s;
  background: #ffffff;
}
.contact_page .box_info .spt {
  box-shadow: 0 0 7px 3px rgba(0, 0, 0, 0.1);
}
.contact_page .box_info .spt .item_spt {
  height: 165px;
  padding: 33px 70px 39px 30px;
  background: #ffffff;
  color: #303030;
  float: left;
  width: 100%;
  border: 1px solid #eeeeee;
}
.contact_page .box_info .spt .item_spt.bg_ {
  background: #0567FA;
  color: #ffffff;
}
.contact_page .box_info .spt .item_spt.bg_ .icon_ {
  background: #ffffff;
  border-color: #ffd9d9;
  color: #0567FA;
}
.contact_page .box_info .spt .icon_ {
  float: left;
  width: 15.55%;
  background: #0567FA;
  border: 3px solid #ffd4be;
  border-radius: 50%;
  height: 42px;
  text-align: center;
  line-height: 36px;
  font-size: 18px;
  color: #ffffff;
}
.contact_page .box_info .spt .add_ {
  float: left;
  width: 80.74%;
  margin-left: 3.71%;
}
.contact_page .box_info .spt .add_ h3 {
  font-size: 24px;
  margin-top: 4px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
}
.contact_page .box_info .spt .add_ dd {
  float: left;
  width: 100%;
  margin: 10px;
}
.contact_page .box_info .spt .add_ dt {
  float: left;
  width: 100%;
}
.contact_page .box_info .spt .add_ dt p {
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  font-size: 14px;
  line-height: 24px;
}
.contact_page .box_info .spt .add_ dt p:first-child {
  margin-top: -7px;
}
.event_main_view {
  margin-top: 74px;
  padding-bottom: 220px;
}
.event_main_view .list_ {
  float: left;
  width: 100%;
  background: #f8f8f8;
  margin-bottom: 30px;
  height: 335px;
}
.event_main_view .box_img {
  float: left;
  width: 34.189%;
  overflow: hidden;
}
.event_main_view .box_img img {
  transition-duration: 0.3s;
}
.event_main_view .box_img:hover img {
  -webkit-filter: grayscale(50%);
  -moz-filter: grayscale(50%);
  transition-duration: 0.3s;
}
.event_main_view .box_sumary_ {
  float: left;
  width: 65.811%;
  padding-left: 35px;
  padding-right: 40px;
  padding-top: 26px;
}
.event_main_view .name_ {
  font-weight: 300;
  color: #303030;
  font-size: 36px;
  float: left;
  margin-top: -5px;
}
.event_main_view .name_:hover {
  color: #0567FA;
}
.event_main_view .date_ {
  float: left;
  width: 100%;
  margin-top: 13px;
}
.event_main_view .date_ li {
  font-family: "Grand Hotel", cursive;
  font-size: 18px;
  color: #aaa;
  float: left;
  margin-right: 28px;
  line-height: 30px;
}
.event_main_view .date_ li:before {
  content: "\f117";
  font-family: "ionicons";
  color: #0567FA;
  margin-right: 5px;
  font-size: 15px;
}
.event_main_view .date_ li.loca_ {
  width: 100%;
  margin-right: 0;
}
.event_main_view .date_ li.loca_:before {
  content: "\f456";
  font-size: 18px;
}
.event_main_view .sum_ {
  float: left;
  width: 100%;
  margin-top: 19px;
}
.event_main_view .sum_ p {
  line-height: 24px;
  color: #686868;
}
.event_main_view .view_detail {
  margin-top: 25px;
  float: left;
  width: 200px;
  height: 42px;
  line-height: 40px;
  border-radius: 50px;
  font-weight: 700;
  color: #ffffff;
  background: #0567FA;
  text-align: center;
  border: 1px solid #0567FA;
}
.event_main_view .view_detail:hover {
  background: #ffffff;
  color: #0567FA;
}
.event_main_view .navigation {
  float: right;
  margin-top: 70px;
}
.event_main_view .navigation li {
  height: 36px;
  width: 36px;
  float: left;
  text-align: center;
  line-height: 36px;
  margin-left: 10px;
}
.event_main_view .navigation li a {
  border: 1px solid #aaaaaa;
  color: #777777;
  border-radius: 3px;
  float: left;
  width: 100%;
  height: 100%;
}
.event_main_view .navigation li a:hover {
  border-color: #0567FA;
}
.event_main_view .navigation li a.natv {
  border-color: transparent;
  color: #ffffff;
  background: #0567FA;
  border-bottom: 3px solid #da5c18;
  cursor: default;
}
.event_detail {
  padding-top: 0px;
  padding-bottom: 0px;
}
.event_detail .top_fly {
  padding: 40px;
  background: #303030;
  height: 500px;
  border-radius: 20px;
}
.event_detail .top_fly .fly_carousel {
  float: left;
  width: 32.111%;
  position: relative;
  padding: 9px;
}
.event_detail .top_fly .fly_carousel .fly_crs .item_crs img {
  width: 100%;
}
.event_detail .top_fly .fly_carousel .fly_crs .slick-dots {
  position: absolute;
  bottom: -20px;
  text-align: center;
  width: 100%;
}
.event_detail .top_fly .fly_carousel .fly_crs .slick-dots li {
  display: inline-block;
  width: 7px;
  height: 8px;
  margin: 0 2px;
}
.event_detail .top_fly .fly_carousel .fly_crs .slick-dots li.slick-active button {
  border: 1px solid #dc682a;
  background: transparent;
}
.event_detail .top_fly .fly_carousel .fly_crs .slick-dots li button {
  font-size: 0;
  background: #454545;
  cursor: pointer;
  border: 0;
  float: left;
  width: 100%;
  height: 100%;
  padding: 0;
  border-radius: 50%;
}
.event_detail .top_fly .fly_carousel .tl_ {
  position: absolute;
  left: 0;
  top: 0;
  width: 47px;
  height: 28px;
  border-top: 1px solid #0567FA;
  border-left: 1px solid #0567FA;
}
.event_detail .top_fly .fly_carousel .tr_ {
  position: absolute;
  right: 0;
  top: 0;
  width: 47px;
  height: 28px;
  border-top: 1px solid #0567FA;
  border-right: 1px solid #0567FA;
}
.event_detail .top_fly .fly_carousel .bl_ {
  position: absolute;
  left: 0;
  bottom: 0;
  width: 47px;
  height: 28px;
  border-bottom: 1px solid #0567FA;
  border-left: 1px solid #0567FA;
}
.event_detail .top_fly .fly_carousel .br_ {
  position: absolute;
  right: 0;
  bottom: 0;
  width: 47px;
  height: 28px;
  border-bottom: 1px solid #0567FA;
  border-right: 1px solid #0567FA;
}
.event_detail .top_fly .fly_calendar {
  float: right;
  width: 64.221%;
}
.event_detail .top_fly .fly_calendar .name_ {
  font-weight: 300;
  color: #ffffff;
  font-size: 48px;
  float: left;
  margin-top: -8px;
}
.event_detail .top_fly .fly_calendar .name_:hover {
  color: #0567FA;
}
.event_detail .top_fly .fly_calendar .date_ {
  float: left;
  width: 100%;
  margin-top: 13px;
}
.event_detail .top_fly .fly_calendar .date_ li {
  font-family: "Grand Hotel", cursive;
  font-size: 18px;
  color: #aaa;
  float: left;
  margin-right: 28px;
  line-height: 30px;
}
.event_detail .top_fly .fly_calendar .date_ li:before {
  content: "\f117";
  font-family: "ionicons";
  color: #0567FA;
  margin-right: 5px;
  font-size: 15px;
}
.event_detail .top_fly .fly_calendar .date_ li.loca_ {
  width: 100%;
  margin-right: 0;
}
.event_detail .top_fly .fly_calendar .date_ li.loca_:before {
  content: "\f456";
  font-size: 18px;
}
.event_detail .top_fly .fly_calendar .fly_form {
  float: left;
  width: 100%;
  margin-top: 40px;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ {
  float: left;
  width: 280px;
  margin-right: 61px;
  margin-bottom: 16px;
}
.event_detail .top_fly .fly_calendar .fly_form .box_.select_ {
  position: relative;
}
.event_detail .top_fly .fly_calendar .fly_form .box_.select_:after {
  content: "\f35f";
  font-family: "ionicons";
  color: #aaaaaa;
  position: absolute;
  bottom: 10px;
  right: 24px;
  font-size: 22px;
}
.event_detail .top_fly .fly_calendar .fly_form .box_.select_ select {
  -webkit-appearance: none;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ label {
  float: left;
  width: 100%;
  margin-bottom: 8px;
  color: #aaaaaa;
  font-size: 14px;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ label span {
  color: #0567FA;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ select {
  background: transparent;
  border: 1px solid #aaaaaa;
  color: #aaaaaa;
  font-size: 14px;
  border-radius: 3px;
  height: 42px;
  padding: 0 24px;
  font-weight: 700;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ select:focus {
  border-color: #0567FA;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ input {
  background: transparent;
  border: 1px solid #aaaaaa;
  color: #aaaaaa;
  font-size: 14px;
  border-radius: 3px;
  height: 42px;
  padding: 0 24px;
  font-weight: 700;
  position: relative;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ input:focus {
  border-color: #0567FA;
}
.event_detail .top_fly .fly_calendar .fly_form .box_.number_ {
  position: relative;
  background: url(../images/ar.png) no-repeat right 25px bottom 13px;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ input[type="number"]::-webkit-outer-spin-button {
  -webkit-appearance: none;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ input[type="number"]::-webkit-inner-spin-button {
  -webkit-appearance: none;
  height: 17px;
  margin-top: 10px;
  width: 11px;
  margin-right: -4px;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ input[type="number"]::-webkit-inner-spin-button:hover {
  opacity: .8;
}
.event_detail .top_fly .fly_calendar .fly_form .box_ input[type="number"]::-webkit-inner-spin-button:active {
  opacity: .8;
}
.event_detail .top_fly .fly_calendar .fly_form .box_:nth-of-type(2n) {
  margin-right: 0;
}
.event_detail .top_fly .fly_calendar .fly_form .btn_ {
  float: left;
  width: 100%;
  padding-left: 9%;
  margin-top: 24px;
}
.event_detail .top_fly .fly_calendar .fly_form .btn_ li {
  display: inline-block;
  margin: 0 13.5px;
}
.event_detail .top_fly .fly_calendar .fly_form .btn_ li span {
  color: #0567FA;
  font-family: "Grand Hotel", cursive;
  font-size: 24px;
  font-weight: 400;
}
.event_detail .top_fly .fly_calendar .fly_form .btn_ li button {
  width: 200px;
  height: 42px;
  line-height: 40px;
  border: 0;
  text-align: center;
  text-transform: uppercase;
  font-weight: 700;
  color: #ffffff;
  background: #0567FA;
  font-size: 14px;
  border-radius: 50px;
  cursor: pointer;
  transition-duration: 0.5s;
}
.event_detail .top_fly .fly_calendar .fly_form .btn_ li button:hover {
  background: #ffffff;
  color: #0567FA;
  transition-duration: 0.5s;
}
.event_detail .event_ {
  margin-top: 73px;
}
.event_detail .event_ .tt_ {
  float: left;
  width: 100%;
  font-weight: 300;
  font-size: 36px;
  margin-top: -7px;
  margin-bottom: 37px;
}
.event_detail .event_ .box_rate_ {
  top: -55px;
  padding-top: 8px;
  border-radius: 20px;
  float: center;
  width: 100%;
  border: 5px solid #CCCCCC;
  background: #0066FF;
  height: 200px;
  margin-bottom: -50px;
  position: relative;
  overflow: hidden;
    text-align: right -10px;

}
.event_detail .event_ .box_rate_:hover {
  background: rgba(255,0,0,0.9);
  transition-duration: 0.5s;
}
.event_detail .event_ .box_rate_:hover .cont_ a {
  color: #ffffff;
}
.event_detail .event_ .box_rate_:hover .cont_ p {
  color: #838383;
}
.event_detail .event_ .box_rate_ .box_img {
  position: absolute;
  z-index: -1;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
}
.event_detail .event_ .box_rate_ .box_img img {
  width: 100%;
  height: 100%;
}
.event_detail .event_ .box_rate_ .icon_ {
  font-size: 72px;
  color: #0567FA;
  line-height: 1;
  float: left;
  width: 23.24%;
  text-align: center;
  display: block;
  margin-top: -5px;
}
.event_detail .event_ .box_rate_ .icon_ .ion-ios-musical-note {
  position: relative;
}
.event_detail .event_ .box_rate_ .icon_ .ion-ios-musical-note:after {
  position: absolute;
  right: -3px;
  content: "\f46b";
  font-family: "ionicons";
}
.event_detail .event_ .box_rate_ .cont_ {
  float: left;
  width: 76.76%;
  padding-right: 30px;
}
.event_detail .event_ .box_rate_ .cont_ a {
  font-size: 24px;
  color: #303030;
  font-weight: 300;
  float: left;
  margin-top: -4px;
}
.event_detail .event_ .box_rate_ .cont_ a:hover {
  color: #0567FA;
}
.event_detail .event_ .box_rate_ .cont_ dl {
  float: left;
  width: 100%;
  margin-top: 9px;
  margin-bottom: 16px;
}
.event_detail .event_ .box_rate_ .cont_ dl dt {
  float: left;
  color: #0567FA;
  font-size: 18px;
  font-family: "Grand Hotel", cursive;
}
.event_detail .event_ .box_rate_ .cont_ dl dd {
  float: left;
  margin-left: 22px;
  padding-top: 2px;
}
.event_detail .event_ .box_rate_ .cont_ dl dd span {
  color: #f9ce3a;
  float: left;
  margin-right: 1px;
}
.event_detail .event_ .box_rate_ .cont_ p {
  line-height: 24px;
  float: left;
}
.event_detail .about_event .tt_ {
  float: left;
  width: 100%;
  font-weight: 300;
  font-size: 36px;
  margin-top: 37px;
  margin-bottom: 27px;
}
.event_detail .about_event .left_ {
  float: left;
  width: 50%;
  padding-right: 85px;
}
.event_detail .about_event .left_ p {
  color: #777;
  line-height: 24px;
  margin-bottom: 15px;
}
.event_detail .about_event .left_ p b {
  color: #0567FA;
}
.event_detail .about_event .left_ p i {
  font-style: italic;
  text-decoration: underline;
}
.event_detail .about_event .box_video {
  float: right;
  width: 50%;
  position: relative;
}
.event_detail .about_event .box_video:before {
  content: "";
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  position: absolute;
  background: rgba(242, 111, 41, 0.2);
}
.event_detail .about_event .box_video .vd_event_detail {
  position: absolute;
  top: 50%;
  left: 50%;
  height: 60px;
  width: 60px;
  margin-left: -30px;
  margin-top: -30px;
  background: #0567FA;
  border-radius: 50%;
  line-height: 58px;
  cursor: pointer;
  border: 1px solid transparent;
  transition-duration: 0.4s;
}
.event_detail .about_event .box_video .vd_event_detail:hover {
  background: #ffffff;
  border-color: #0567FA;
  transition-duration: 0.4s;
}
.event_detail .about_event .box_video .vd_event_detail:hover:before {
  color: #0567FA;
  transition-duration: 0.4s;
}
.event_detail .about_event .box_video .vd_event_detail:before {
  content: "\f215";
  font-family: "ionicons";
  color: #ffffff;
  font-size: 36px;
  position: relative;
  left: 50%;
  margin-left: -7px;
}
.event_detail .about_event .txt {
  float: left;
  width: 100%;
  margin-top: 20px;
}
.event_detail .about_event .txt p {
  color: #777;
  line-height: 24px;
  margin-bottom: 15px;
}
.event_detail .about_event .txt i {
  font-style: italic;
  text-decoration: underline;
}
.event_detail .classes_related {
  border-top: 5px solid #f1f1f1;
  margin-top: 78px;
  padding-top: 66px;
}
.event_detail .classes_related .name_ {
  float: left;
  width: 100%;
}
.event_detail .classes_related .name_ h3 {
  font-size: 36px;
  font-weight: 300;
}
.event_detail .classes_related .box_pro {
  margin-top: 36px;
}
.event_detail .classes_related .box_pro .item_pro {
  float: left;
  width: 23.077%;
  margin-right: 2.564%;
}
.event_detail .classes_related .box_pro .item_pro:nth-child(4n) {
  margin-right: 0;
}
.event_detail .classes_related .box_pro .box_img {
  position: relative;
  width: 100%;
  height: 180px;
  border-radius: 20px;
  overflow: hidden;
}
.event_detail .classes_related .box_pro .box_img img {
  height: 100%;
}
.event_detail .classes_related .box_pro .box_img:hover .pro_img {
  opacity: 0.8;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.event_detail .classes_related .box_pro .box_img:hover .overlay {
  position: absolute;
  background: rgba(242, 111, 41, 0.5);
  left: 5px;
  top: 5px;
  right: 5px;
  bottom: 5px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.event_detail .classes_related .box_pro .box_img:hover .overlay a {
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
  top: 50%;
  opacity: 1;
}
.event_detail .classes_related .box_pro .box_img .pro_img {
  width: 100%;
  border-radius: 20px;
}
.event_detail .classes_related .box_pro .nav_ {
  float: left;
  width: 100%;
  position: relative;
  margin-top: 17px;
}
.event_detail .classes_related .box_pro .nav_.first_ {
  margin-bottom: 7px;
}
.event_detail .classes_related .box_pro .nav_.dot_ {
  margin-bottom: 19px;
}
.event_detail .classes_related .box_pro .nav_.dot_:before {
  position: absolute;
  content: "";
  height: 1px;
  width: 60px;
  background: #f1f1f1;
  bottom: -19px;
  left: 0;
}
.event_detail .classes_related .box_pro .nav_ a {
  color: #303030;
  font-size: 24px;
  font-weight: 300;
  margin-top: -6px;
  margin-left: -4px;
}
.event_detail .classes_related .box_pro .nav_ a:hover {
  color: #0567FA;
}
.event_detail .classes_related .box_pro .sum {
  float: left;
  width: 100%;
  color: #0567FA;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  margin-top: 10px;
  font-size: 18px;
}
.event_detail .classes_related .box_pro .overlay {
  position: absolute;
  border-radius: 20px;
  left: 50%;
  top: 50%;
  right: 50%;
  bottom: 50%;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.event_detail .classes_related .box_pro .overlay a {
  position: absolute;
  margin-top: -15px;
  margin-left: -15px;
  left: 50%;
  top: -100%;
  opacity: 0;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
.page_blog {
  padding-bottom: 220px;
}
.page_blog .blog_mainview {
  margin-top: 90px;
}
.page_blog .post_ {
  float: left;
  width: 100%;
  padding-bottom: 60px;
  position: relative;
}
.page_blog .post_:after {
  content: "";
  height: 3px;
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  background: url(../images/dbdas.png) repeat-x;
}
.page_blog .post_ .box_ {
  float: left;
  width: 100%;
  position: relative;
  overflow: hidden;
  margin-top: 60px;
  border: 10px solid #f8f8f8;
  border-radius: 20px;
}
.page_blog .post_ .box_img {
  height: 380px;
}
.page_blog .post_ .box_img img {
  width: 100%;
}
.page_blog .post_ .box_carousel {
  height: 400px;
  z-index: 2;
}
.page_blog .post_ .box_carousel .slick-arrow {
  position: absolute;
  top: 50%;
  z-index: 2;
  font-size: 0;
  width: 37px;
  height: 50px;
  background: rgba(255, 255, 255, 0.7);
  border: 0;
  cursor: pointer;
  margin-top: -25px;
  transition-duration: 0.5s;
}
.page_blog .post_ .box_carousel .slick-arrow:hover {
  background: #ffffff;
  transition-duration: 0.5s;
}
.page_blog .post_ .box_carousel .slick-arrow:before {
  font-family: FontAwesome;
  font-size: 18px;
  color: #777;
}
.page_blog .post_ .box_carousel .slick-prev {
  left: 0;
  border-radius: 0 3px 3px 0;
}
.page_blog .post_ .box_carousel .slick-prev:before {
  content: "\f104";
}
.page_blog .post_ .box_carousel .slick-next {
  right: 0;
  border-radius: 3px 0 0 3px;
}
.page_blog .post_ .box_carousel .slick-next:before {
  content: "\f105";
}
.page_blog .post_ .box_carousel img {
  width: 100%;
}
.page_blog .post_ .box_audio audio {
  width: 100%;
}
.page_blog .post_ .box_link {
  height: 224px;
  background: #56b2cf;
  padding: 42px 20px;
  padding-right: 100px;
}
.page_blog .post_ .box_link .cp_link {
  position: absolute;
  right: 20px;
  top: 20px;
  width: 54px;
  height: 54px;
  border-radius: 50%;
  background: #ffffff;
  border: 3px solid #c6f1ff;
  text-align: center;
  line-height: 48px;
}
.page_blog .post_ .box_link .cp_link:hover {
  background: #56b2cf;
  border-color: #ffffff;
}
.page_blog .post_ .box_link .cp_link:hover a {
  color: #ffffff;
}
.page_blog .post_ .box_link .cp_link a {
  font-size: 36px;
  color: #56b2cf;
}
.page_blog .post_ .box_link:hover .link {
  border-top: 1px solid #ccc;
  transition-duration: 0.5s;
}
.page_blog .post_ .box_link h3 {
  font-weight: 300;
  font-size: 36px;
  color: #ffffff;
  white-space: pre-line;
  line-height: 48px;
  margin-top: -13px;
}
.page_blog .post_ .box_link .link {
  position: absolute;
  left: 0;
  width: 100%;
  height: 48px;
  border-top: 1px solid #ecf0f1;
  bottom: 0;
  padding-left: 19px;
  line-height: 45px;
}
.page_blog .post_ .box_link .link a {
  color: #ffffff;
  font-weight: 700;
  font-style: italic;
}
.page_blog .post_ .box_link .link a:hover {
  text-decoration: underline;
}
.page_blog .post_ .box_video {
  height: 450px;
}
.page_blog .post_ .name_ {
  float: left;
  width: 100%;
  margin-top: 25px;
  margin-bottom: 16px;
}
.page_blog .post_ .name_ .btn_name {
  font-weight: 300;
  font-size: 36px;
  color: #303030;
}
.page_blog .post_ .name_ .btn_name:hover {
  color: #0567FA;
}
.page_blog .post_ .list_if {
  float: left;
  width: 100%;
  margin-top: -5px;
}
.page_blog .post_ .list_if li {
  float: left;
  border-right: 2px solid #999;
  padding-right: 12px;
  margin-right: 12px;
  font-size: 18px;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  color: #777;
}
.page_blog .post_ .list_if li a {
  color: #0567FA;
}
.page_blog .post_ .list_if li a:hover {
  text-decoration: underline;
}
.page_blog .post_ .list_if li:last-of-type {
  border-right: 0;
}
.page_blog .post_ .das {
  float: left;
  width: 100%;
  height: 1px;
  background: url(../images/das.png) no-repeat top left;
  margin-top: 26px;
  margin-bottom: 10px;
}
.page_blog .post_ .sum_ {
  float: left;
  width: 100%;
}
.page_blog .post_ .sum_ p {
  line-height: 24px;
}
.page_blog .post_ .btn_rm {
  width: 160px;
  height: 50px;
  line-height: 48px;
  text-align: center;
  border: 1px solid #0567FA;
  background: #ffffff;
  color: #0567FA;
  text-transform: uppercase;
  font-size: 16px;
  font-weight: 700;
  float: left;
  border-radius: 50px;
  margin-top: 23px;
}
.page_blog .post_ .btn_rm:hover {
  background: #0567FA;
  color: #ffffff;
}
.page_blog .navigation {
  float: right;
  margin-top: 60px;
}
.page_blog .navigation li {
  height: 36px;
  width: 36px;
  float: left;
  text-align: center;
  line-height: 36px;
  margin-left: 10px;
}
.page_blog .navigation li a {
  border: 1px solid #aaaaaa;
  color: #777777;
  border-radius: 3px;
  float: left;
  width: 100%;
  height: 100%;
}
.page_blog .navigation li a:hover {
  border-color: #0567FA;
}
.page_blog .navigation li a.natv {
  border-color: transparent;
  color: #ffffff;
  background: #0567FA;
  border-bottom: 3px solid #da5c18;
  cursor: default;
}
.page_blog .sidebar {
  margin-top: 90px;
}
.page_blog .sidebar .search_ {
  float: left;
  width: 100%;
  position: relative;
  margin-bottom: 55px;
}
.page_blog .sidebar .search_ input[type="text"] {
  float: left;
  width: 100%;
  height: 40px;
  border: 1px solid #eeeeee;
  border-radius: 3px;
  padding: 0 40px 0 20px;
}
.page_blog .sidebar .search_ input[type="text"]:focus {
  border-color: #303030;
  transition-duration: 0.5s;
}
.page_blog .sidebar .search_ input[type="text"]::-webkit-input-placeholder {
  color: #777;
}
.page_blog .sidebar .search_ input[type="text"]::-moz-placeholder {
  color: #777;
}
.page_blog .sidebar .search_ button {
  position: absolute;
  top: 0;
  right: 0;
  font-size: 18px;
  color: #777;
  background: transparent;
  border: 0;
  cursor: pointer;
  height: 40px;
  width: 40px;
}
.page_blog .sidebar .title_ {
  float: left;
  width: 100%;
}
.page_blog .sidebar .title_ h3 {
  font-weight: 300;
  color: #333;
  font-size: 24px;
  margin-top: -4px;
  margin-bottom: -5px;
}
.page_blog .sidebar .cate_ {
  float: left;
  width: 100%;
  margin-top: 32px;
  margin-bottom: 36px;
}
.page_blog .sidebar .cate_ li {
  float: left;
  width: 100%;
  position: relative;
  margin-bottom: 18px;
}
.page_blog .sidebar .cate_ li a {
  color: #777;
}
.page_blog .sidebar .cate_ li a:before {
  content: "\f105";
  font-family: FontAwesome;
  margin-right: 19px;
}
.page_blog .sidebar .cate_ li a:hover {
  color: #0567FA;
}
.page_blog .sidebar .cate_ li a:hover + span {
  color: #ffffff;
  background: #0567FA;
}
.page_blog .sidebar .cate_ li span {
  position: absolute;
  top: 0;
  right: 0;
  font-size: 13px;
  color: #0567FA;
  background: #ffffff;
  display: block;
  border: 1px solid #0567FA;
  width: 37px;
  height: 22px;
  text-align: center;
  line-height: 20px;
  border-radius: 11px;
}
.page_blog .sidebar .new_post {
  float: right;
  width: 100%;
  margin-bottom: 34px;
  margin-top: 33px;
}
.page_blog .sidebar .new_post .tabs_menu {
  float: right;
  width: 100%;
  clear: both;
}
.page_blog .sidebar .new_post .tabs_menu li {
  float: right;
  width: 50%;
  height: 46px;
  position: relative;
}
.page_blog .sidebar .new_post .tabs_menu li span {
  position: absolute;
  left: 0;
  top: -4px;
  height: 4px;
  width: 0;
  background: #ffffff;
}
.page_blog .sidebar .new_post .tabs_menu li a {
  text-align: center;
  color: #ffffff;
  background: #777777;
  float: left;
  width: 100%;
  height: 100%;
  line-height: 50px;
  font-weight: 700;
}
.page_blog .sidebar .new_post .tabs_menu li.tab_current span {
  width: 100%;
  background: #0567FA;
  transition-duration: 0.5s;
}
.page_blog .sidebar .new_post .tabs_menu li.tab_current a {
  background: #303030;
}
.page_blog .sidebar .new_post .tab {
  float: right;
  width: 100%;
}
.page_blog .sidebar .new_post .tab_content {
  width: 100%;
  display: none;
  padding-top: 30px;
}
.page_blog .sidebar .new_post .tab_content .item_post_ {
  float: right;
  width: 100%;
  padding-bottom: 20px;
  padding-top: 20px;
  border-bottom: 1px solid #eeeeee;
}
.page_blog .sidebar .new_post .tab_content .item_post_:last-of-type {
  border-bottom: 0;
}
.page_blog .sidebar .new_post .tab_content .item_post_ .box_img {
  float: right;
  height: 80px;
  width: 37.038%;
  overflow: hidden;
  border-radius: 3px;
}
.page_blog .sidebar .new_post .tab_content .item_post_ .box_img img {
  height: 100%;
  width: 100%;
}
.page_blog .sidebar .new_post .tab_content .item_post_ .suma_ {
  float: right;
  width: 62.962%;
  padding-left: 14px;
}
.page_blog .sidebar .new_post .tab_content .item_post_ .suma_ dt {
  float: right;
  width: 100%;
  position: relative;
  margin-bottom: 2px;
}
.page_blog .sidebar .new_post .tab_content .item_post_ .suma_ dt .date {
  color: #777;
  font-family: "Grand Hotel", cursive;
  font-size: 14px;
  font-weight: 400;
}
.page_blog .sidebar .new_post .tab_content .item_post_ .suma_ dt .cmt {
  position: absolute;
  top: 0;
  right: 0;
  font-size: 14px;
  color: #ccc;
  font-family: "Grand Hotel", cursive;
}
.page_blog .sidebar .new_post .tab_content .item_post_ .suma_ dt .cmt:before {
  content: "\f0e6";
  font-family: FontAwesome;
  margin-right: 3px;
}
.page_blog .sidebar .new_post .tab_content .item_post_ .suma_ dd {
  float: right;
  width: 100%;
}
.page_blog .sidebar .new_post .tab_content .item_post_ .suma_ dd .btn_link {
  font-weight: 700;
  color: #303030;
  line-height: 24px;
}
.page_blog .sidebar .new_post .tab_content .item_post_ .suma_ dd .btn_link:hover {
  color: #0567FA;
}
.page_blog .sidebar .new_post .tab_content.tab_block {
  display: block;
}
.page_blog .sidebar .archives_ {
  float: right;
  width: 100%;
  margin-bottom: 28px;
  margin-top: 10px;
}
.page_blog .sidebar .archives_ li {
  float: right;
  width: 100%;
  position: relative;
  border-bottom: 1px solid #eeeeee;
  height: 50px;
  line-height: 49px;
}
.page_blog .sidebar .archives_ li a {
  color: #777;
}
.page_blog .sidebar .archives_ li a:hover {
  color: #0567FA;
}
.page_blog .sidebar .archives_ li a:hover + span {
  color: #ffffff;
  background: #0567FA;
}
.page_blog .sidebar .archives_ li span {
  position: absolute;
  top: 18px;
  right: 0;
  font-size: 13px;
  color: #0567FA;
  background: #ffffff;
  display: block;
  border: 1px solid #0567FA;
  width: 37px;
  height: 22px;
  text-align: center;
  line-height: 20px;
  border-radius: 11px;
}
.page_blog .sidebar .social_ {
  float: right;
  width: 100%;
  margin-top: 32px;
  margin-bottom: 55px;
}
.page_blog .sidebar .social_ li {
  float: right;
  margin-right: 3.5552%;
  width: 37px;
}
.page_blog .sidebar .social_ li:last-of-type {
  margin-right: 0;
}
.page_blog .sidebar .social_ li a {
  width: 100%;
  height: 37px;
  border-radius: 3px;
  float: right;
  font-size: 18px;
  color: #ffffff;
  text-align: center;
  line-height: 37px;
}
.page_blog .sidebar .social_ li a:hover {
  border-radius: 50%;
}
.page_blog .sidebar .social_ li a.ion-social-facebook {
  background: #1883d5;
}
.page_blog .sidebar .social_ li a.ion-social-twitter {
  background: #21c2f8;
}
.page_blog .sidebar .social_ li a.fa-pinterest-p {
  background: #ef584d;
}
.page_blog .sidebar .social_ li a.ion-social-googleplus-outline {
  background: #2c3e50;
}
.page_blog .sidebar .social_ li a.ion-social-tumblr {
  background: #43698f;
}
.page_blog .sidebar .social_ li a.ion-social-dribbble-outline {
  background: #eb5d8c;
}
.page_blog .sidebar .tag_ {
  float: left;
  width: 100%;
  margin-top: 33px;
}
.page_blog .sidebar .tag_ li a {
  float: left;
  color: #777;
  background: #ffefe7;
  border-radius: 3px;
  padding: 8px 11px;
  margin-right: 5px;
  margin-bottom: 5px;
}
.page_blog .sidebar .tag_ li a.themforest {
  color: #ffffff;
  background: #0567FA;
}
.page_blog .sidebar .tag_ li a:hover {
  color: #ffffff;
  background: #0567FA;
}
.page_blog .blog_single_content {
  margin-top: 80px;
}
.page_blog .blog_single_content .box_img_top {
  float: left;
  width: 100%;
  height: 500px;
  border-radius: 20px;
  overflow: hidden;
  border: 10px solid #f8f8f8;
}
.page_blog .blog_single_content .box_img_top img {
  width: 100%;
}
.page_blog .blog_single_content .name_ {
  float: left;
  width: 100%;
  margin-top: 25px;
  margin-bottom: 16px;
}
.page_blog .blog_single_content .name_ .btn_name {
  font-weight: 300;
  font-size: 36px;
  color: #303030;
}
.page_blog .blog_single_content .name_ .btn_name:hover {
  color: #0567FA;
}
.page_blog .blog_single_content .list_if {
  float: left;
  width: 100%;
  margin-top: -5px;
}
.page_blog .blog_single_content .list_if li {
  float: left;
  border-right: 2px solid #999;
  padding-right: 12px;
  margin-right: 12px;
  font-size: 18px;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  color: #777;
}
.page_blog .blog_single_content .list_if li a {
  color: #0567FA;
}
.page_blog .blog_single_content .list_if li a:hover {
  text-decoration: underline;
}
.page_blog .blog_single_content .list_if li:last-of-type {
  border-right: 0;
}
.page_blog .blog_single_content .content_view {
  border-top: 1px solid #ecf0f1;
  margin-top: 33px;
  padding-top: 21px;
}
.page_blog .blog_single_content .content_view .txt {
  float: left;
  width: 100%;
}
.page_blog .blog_single_content .content_view .txt h3 {
  font-size: 30px;
  font-weight: 300;
  margin-top: 36px;
  margin-bottom: 3px;
}
.page_blog .blog_single_content .content_view .txt b {
  line-height: 30px;
  font-size: 18px;
  color: #777;
}
.page_blog .blog_single_content .content_view .txt p {
  margin-top: 18px;
  color: #777;
  line-height: 24px;
  float: left;
  width: 100%;
}
.page_blog .blog_single_content .content_view .txt .box_img {
  float: left;
  height: 400px;
  margin-top: 22px;
  width: 42.53%;
  border-radius: 5px;
  border: 5px solid #f8f8f8;
  overflow: hidden;
}
.page_blog .blog_single_content .content_view .txt .box_img img {
  border-radius: 5px;
  width: 100%;
  height: 100%;
}
.page_blog .blog_single_content .content_view .txt .text {
  float: left;
  width: 57.47%;
  padding-left: 22px;
}
.page_blog .blog_single_content .content_view .quote {
  margin: 35px 0;
  float: left;
  width: 100%;
  height: 165px;
  border: 1px solid #f6f6f6;
  position: relative;
  z-index: 2;
  padding-left: 60px;
  padding-top: 40px;
  padding-right: 140px;
  border-radius: 0 20px 20px 0;
  background: #ffffff url(../images/quote.png) no-repeat top 42px right 59px;
}
.page_blog .blog_single_content .content_view .quote:before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 9px;
  height: 100%;
  background: #56b2cf;
  z-index: 1;
}
.page_blog .blog_single_content .content_view .quote h3 {
  font-size: 24px;
  font-weight: 900;
  font-style: italic;
  color: #777;
  margin-bottom: 8px;
}
.page_blog .blog_single_content .content_view .quote p {
  font-weight: 700;
  font-style: italic;
  color: #777;
  line-height: 26px;
}
.page_blog .blog_single_content .content_view .letter_ p {
  color: #777;
  line-height: 24px;
  float: left;
  width: 100%;
}
.page_blog .blog_single_content .content_view .letter_ p:first-letter {
  font-size: 30px;
  font-weight: 900;
  color: #ffffff;
  background: #0567FA;
  width: 40px;
  padding: 0 10px;
  height: 40px;
  border-radius: 3px;
  text-align: center;
  line-height: 40px;
  float: left;
  margin-right: 9px;
}
.page_blog .blog_single_content .content_view .left_ {
  float: left;
  width: 50%;
  margin-top: 24px;
}
.page_blog .blog_single_content .content_view .left_ li {
  float: left;
  margin-bottom: 14px;
  width: 100%;
}
.page_blog .blog_single_content .content_view .left_ li.close_:before {
  content: "\f00d";
}
.page_blog .blog_single_content .content_view .left_ li:before {
  content: "\f00c";
  font-family: FontAwesome;
  color: #ffffff;
  background: #34495e;
  font-size: 10px;
  height: 16px;
  width: 16px;
  float: left;
  text-align: center;
  line-height: 16px;
  margin-right: 19px;
  border-radius: 2px;
}
.page_blog .blog_single_content .content_view .right_ {
  float: left;
  width: 50%;
  margin-top: 24px;
}
.page_blog .blog_single_content .content_view .right_ li {
  float: left;
  margin-bottom: 14px;
  width: 100%;
}
.page_blog .blog_single_content .content_view .right_ li.close_:before {
  content: "\f00d";
}
.page_blog .blog_single_content .content_view .right_ li:before {
  content: "\f00c";
  font-family: FontAwesome;
  background: #ffffff;
  color: #a1b1bc;
  border: 1px solid #a1b1bc;
  height: 16px;
  width: 16px;
  float: left;
  margin-right: 19px;
  text-align: center;
  line-height: 16px;
  border-radius: 2px;
  font-size: 10px;
}
.page_blog .blog_single_content .content_view .tag_ {
  float: left;
  width: 100%;
  margin-top: 60px;
  margin-bottom: 30px;
}
.page_blog .blog_single_content .content_view .tag_ li {
  float: left;
}
.page_blog .blog_single_content .content_view .tag_ li a {
  float: left;
  text-align: center;
  height: 25px;
  line-height: 23px;
  color: #ccc;
  border: 1px solid #eeeeee;
  border-radius: 24px;
  padding: 0 13px;
  margin-right: 5px;
  font-style: italic;
}
.page_blog .blog_single_content .content_view .tag_ li a:hover {
  background: #0567FA;
  color: #ffffff;
}
.page_blog .blog_single_content .content_view .tag_ li a.atv {
  background: #0567FA;
  color: #ffffff;
}
.page_blog .blog_single_content .content_view .social_if {
  float: left;
  width: 100%;
  border-top: 1px solid #eeeeee;
  padding-top: 20px;
}
.page_blog .blog_single_content .content_view .social_if .left_l {
  float: left;
  margin-top: 6px;
}
.page_blog .blog_single_content .content_view .social_if .left_l li {
  float: left;
  color: #cccccc;
  font-size: 16px;
  font-family: "Grand Hotel", cursive;
  margin-right: 32px;
}
.page_blog .blog_single_content .content_view .social_if .left_l li span {
  margin-right: 6px;
}
.page_blog .blog_single_content .content_view .social_if .left_l li:nth-of-type(2) {
  color: #0567FA;
}
.page_blog .blog_single_content .content_view .social_if .right_r {
  float: right;
  padding-right: 8px;
}
.page_blog .blog_single_content .content_view .social_if .right_r li {
  float: left;
}
.page_blog .blog_single_content .content_view .social_if .right_r li a {
  font-size: 12px;
  color: #ffffff;
  width: 26px;
  height: 26px;
  float: left;
  text-align: center;
  line-height: 26px;
  border-radius: 50%;
  margin-left: 5px;
}
.page_blog .blog_single_content .content_view .social_if .right_r li a:hover {
  border-radius: 0;
  transition-duration: 0.5s;
}
.page_blog .blog_single_content .content_view .social_if .right_r li a.ion-android-favorite-outline {
  background: #ef584d;
}
.page_blog .blog_single_content .content_view .social_if .right_r li a.ion-social-facebook {
  background: #1883d5;
}
.page_blog .blog_single_content .content_view .social_if .right_r li a.ion-social-twitter {
  background: #21c2f8;
}
.page_blog .blog_single_content .content_view .box_admin {
  margin-bottom: 74px;
  float: left;
  width: 100%;
  background: #0567FA;
  border-radius: 5px;
  height: 160px;
  margin-top: 20px;
  padding-top: 27px;
  padding-bottom: 27px;
  padding-right: 27px;
}
.page_blog .blog_single_content .content_view .box_admin .ava_ad {
  float: left;
  width: 18.852%;
  text-align: center;
}
.page_blog .blog_single_content .content_view .box_admin .ava_ad:hover img {
  border-radius: 0;
  transition-duration: 0.5s;
}
.page_blog .blog_single_content .content_view .box_admin .ava_ad img {
  transition-duration: 0.5s;
  width: 106px;
  height: 106px;
  border-radius: 50%;
  border: 3px solid #ffffff;
}
.page_blog .blog_single_content .content_view .box_admin .infor {
  float: left;
  width: 81.148%;
}
.page_blog .blog_single_content .content_view .box_admin .infor .name_ad {
  font-weight: 300;
  font-size: 24px;
  color: #ffffff;
  float: left;
  margin-top: -4px;
}
.page_blog .blog_single_content .content_view .box_admin .infor .name_ad:hover {
  text-decoration: overline;
}
.page_blog .blog_single_content .content_view .box_admin .infor .fea_ {
  margin-top: 10px;
  float: left;
  width: 100%;
  color: #ffffff;
  font-size: 12px;
  font-style: italic;
}
.page_blog .blog_single_content .content_view .box_admin .infor .sumary_ {
  margin-top: 14px;
  line-height: 24px;
  color: #ffffff;
  float: left;
  width: 100%;
}
.page_blog .blog_single_content .content_view .related_post {
  float: left;
  width: 100%;
  border-bottom: 1px solid #eeeeee;
  padding-bottom: 38px;
}
.page_blog .blog_single_content .content_view .related_post .nav_ li span {
  font-size: 16px;
  color: #ccc;
  font-family: "Grand Hotel", cursive;
}
.page_blog .blog_single_content .content_view .related_post .nav_ li span a {
  color: #0567FA;
}
.page_blog .blog_single_content .content_view .related_post .nav_ li h4 {
  margin-top: 2px;
  font-weight: 300;
  font-size: 24px;
  margin-bottom: 12px;
}
.page_blog .blog_single_content .content_view .related_post .nav_ li .btn_link {
  font-size: 13px;
  color: #777;
  line-height: 36px;
}
.page_blog .blog_single_content .content_view .related_post .nav_ li .btn_link:hover:before {
  background: #303030;
  transition-duration: 0.4s;
}
.page_blog .blog_single_content .content_view .related_post .nav_ li .btn_link:hover:after {
  background: #303030;
  transition-duration: 0.4s;
}
.page_blog .blog_single_content .content_view .related_post .nav_.related_l {
  float: left;
}
.page_blog .blog_single_content .content_view .related_post .nav_.related_l .btn_link:before {
  content: "\f177";
  font-family: FontAwesome;
  color: #ffffff;
  background: #56b2cf;
  line-height: 36px;
  height: 36px;
  width: 36px;
  text-align: center;
  float: left;
  border-radius: 50%;
  margin-right: 13px;
}
.page_blog .blog_single_content .content_view .related_post .nav_.related_r {
  float: right;
  text-align: right;
}
.page_blog .blog_single_content .content_view .related_post .nav_.related_r .btn_link:after {
  content: "\f178";
  font-family: FontAwesome;
  color: #ffffff;
  background: #56b2cf;
  line-height: 36px;
  height: 36px;
  width: 36px;
  text-align: center;
  float: right;
  border-radius: 50%;
  margin-left: 14px;
}
.page_blog .blog_single_content .content_view .box_comments {
  float: left;
  width: 100%;
}
.page_blog .blog_single_content .content_view .box_comments .cmt_tt {
  float: left;
  width: 100%;
  font-weight: 300;
  font-size: 36px;
  margin-top: 46px;
  margin-bottom: 47px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_ .user_ava img {
  transition-duration: 0.2s;
}
.page_blog .blog_single_content .content_view .box_comments .comments_ .user_ava:hover img {
  border-radius: 0!important;
  transition-duration: 0.3s;
}
.page_blog .blog_single_content .content_view .box_comments .comments_ .username_:hover {
  text-decoration: underline;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ {
  float: left;
  width: 100%;
  margin-bottom: 27px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .user_ava {
  width: 9.196%;
  float: left;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .user_ava img {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  border: 5px solid #f8f8f8;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .box_content_cmt {
  float: left;
  width: 90.804%;
  padding-left: 14px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .box_content_cmt .box_bb_ {
  padding-bottom: 30px;
  border-bottom: 1px solid #eeeeee;
  float: left;
  width: 100%;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .box_content_cmt .box_bb_ .username_ {
  color: #333;
  font-weight: 700;
  float: left;
  margin-top: -2px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .box_content_cmt .box_bb_ .date_ {
  color: #dddddd;
  font-size: 12px;
  float: left;
  width: 100%;
  font-style: italic;
  margin-top: 7px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .box_content_cmt .box_bb_ .content_cmt {
  color: #797979;
  line-height: 24px;
  float: left;
  width: 100%;
  margin-top: 13px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .box_content_cmt .box_bb_ .btn_reply {
  float: left;
  width: 88px;
  height: 25px;
  border-radius: 25px;
  border: 1px solid #0567FA;
  color: #0567FA;
  font-size: 12px;
  font-weight: 700;
  background: #ffffff;
  line-height: 23px;
  text-align: center;
  text-transform: uppercase;
  margin-top: 18px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .box_content_cmt .box_bb_ .btn_reply:hover {
  background: #0567FA;
  color: #ffffff;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ {
  float: left;
  width: 90.804%;
  margin-left: 9.196%;
  margin-bottom: 27px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .user_ava {
  width: 10.128%;
  float: left;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .user_ava img {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  border: 5px solid #f8f8f8;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .box_content_cmt {
  float: left;
  width: 89.872%;
  padding-left: 14px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .box_content_cmt .box_bb_ {
  padding-bottom: 30px;
  border-bottom: 1px solid #eeeeee;
  float: left;
  width: 100%;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .box_content_cmt .box_bb_ .username_ {
  color: #333;
  font-weight: 700;
  float: left;
  margin-top: -2px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .box_content_cmt .box_bb_ .date_ {
  color: #dddddd;
  font-size: 12px;
  float: left;
  width: 100%;
  font-style: italic;
  margin-top: 7px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .box_content_cmt .box_bb_ .content_cmt {
  color: #797979;
  line-height: 24px;
  float: left;
  width: 100%;
  margin-top: 13px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .box_content_cmt .box_bb_ .btn_reply {
  float: left;
  width: 88px;
  height: 25px;
  border-radius: 25px;
  border: 1px solid #0567FA;
  color: #0567FA;
  font-size: 12px;
  font-weight: 700;
  background: #ffffff;
  line-height: 23px;
  text-align: center;
  text-transform: uppercase;
  margin-top: 18px;
}
.page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .box_content_cmt .box_bb_ .btn_reply:hover {
  background: #0567FA;
  color: #ffffff;
}
.page_blog .blog_single_content .content_view .box_comments .comments_:last-of-type {
  margin-bottom: 0;
}
.page_blog .blog_single_content .content_view .box_comments .comments_:last-of-type .box_bb_ {
  border-bottom: 0!important;
}
.page_blog .blog_single_content .content_view .box_comments .more_cmts {
  float: left;
  width: 100%;
  text-align: center;
  height: 50px;
  line-height: 50px;
  font-weight: 700;
  color: #303030;
  text-transform: uppercase;
  background: #dddddd;
  border-radius: 100px;
  margin-top: 10px;
}
.page_blog .blog_single_content .content_view .box_comments .more_cmts:active {
  background: #ccc;
}
.page_blog .blog_single_content .content_view .box_comments .more_cmts:hover {
  background: #ccc;
}
.page_blog .blog_single_content .content_view .levae_cmt {
  float: left;
  width: 100%;
}
.page_blog .blog_single_content .content_view .levae_cmt .tt_ {
  font-size: 36px;
  font-weight: 300;
  margin-top: 66px;
  margin-bottom: 30px;
}
.page_blog .blog_single_content .content_view .levae_cmt .form_lv {
  float: left;
  width: 100%;
}
.page_blog .blog_single_content .content_view .levae_cmt .form_lv input[type="text"] {
  width: 100%;
  border-radius: 50px;
  height: 50px;
  border: 1px solid #dddddd;
  padding: 0 33px;
}
.page_blog .blog_single_content .content_view .levae_cmt .form_lv input[type="text"]::-webkit-input-placeholder {
  color: #777;
  font-size: 14px;
}
.page_blog .blog_single_content .content_view .levae_cmt .form_lv input[type="text"]::-moz-placeholder {
  color: #777;
  font-size: 14px;
}
.page_blog .blog_single_content .content_view .levae_cmt .form_lv input[type="text"]:focus {
  border-color: #303030;
  transition-duration: 0.5s;
}
.page_blog .blog_single_content .content_view .levae_cmt .req {
  position: relative;
  float: left;
  width: 42.529%;
  margin-bottom: 20px;
}
.page_blog .blog_single_content .content_view .levae_cmt .req:before {
  content: "(*)";
  color: #0567FA;
  top: 17px;
  left: 18px;
  position: absolute;
}
.page_blog .blog_single_content .content_view .levae_cmt .req.reqs {
  margin-left: 3.448%;
  width: 54.023%;
}
.page_blog .blog_single_content .content_view .levae_cmt textarea {
  border: 1px solid #dddddd;
  float: left;
  width: 100%;
  resize: none;
  border-radius: 30px;
  height: 160px;
  padding: 22px 18px;
}
.page_blog .blog_single_content .content_view .levae_cmt textarea::-webkit-input-placeholder {
  color: #777;
  font-size: 14px;
}
.page_blog .blog_single_content .content_view .levae_cmt textarea::-moz-placeholder {
  color: #777;
  font-size: 14px;
}
.page_blog .blog_single_content .content_view .levae_cmt textarea:focus {
  border-color: #303030;
  transition-duration: 0.5s;
}
.page_blog .blog_single_content .content_view .levae_cmt input[type="submit"] {
  margin-top: 20px;
  float: left;
  width: 275px;
  height: 50px;
  font-size: 16px;
  text-transform: uppercase;
  color: #ffffff;
  text-align: center;
  line-height: 48px;
  cursor: pointer;
  font-weight: 700;
  border: 1px solid transparent;
  background: #0567FA;
  border-radius: 50px;
  transition-duration: 0.5s;
}
.page_blog .blog_single_content .content_view .levae_cmt input[type="submit"]:hover {
  transition-duration: 0.5s;
  background: #ffffff;
  color: #0567FA;
  border-color: #0567FA;
}
@media (min-width: 1600px) {
  .top_section .top_box {
    right: 75px;
  }
  .nav {
    position: relative;
  }
}
@media (max-width: 1280px) {
  .hpage .home_search_class .box_right {
    padding-left: 0;
  }
}
@media only screen and (min-width: 1200px) {
  .container {
    width: 1200px;
  }
  ._section_item .container {
    width: 1170px;
  }
}
@media (max-width: 1199px) {
  .top_menu .nav {
    left: 30%;
  }
  ._section_item ._box_item .medal_ h3 {
    font-size: 25px!important;
  }
  ._section_item ._box_item .btn_read {
    bottom: 20px!important;
  }
  ._section_classes .classes_it .box_suma .sumary_ p {
    height: 100px;
    overflow: hidden;
  }
  ._section_classes .classes_it .box_suma .name_ {
    font-size: 25px!important;
  }
  .box_event .container {
    width: 100%;
  }
  ._section_teacher .box_teacher .box_item .teacher_info {
    width: 100%!important;
    background-size: 100%!important;
  }
  ._section_teacher .box_teacher .box_item .teacher_info a {
    font-size: 20px!important;
  }
  .ht_footer .footer_ .footer_main .info li {
    font-size: 12px;
  }
  .hpage .v2_header .top_menu .nav {
    position: static;
  }
  .hpage .v2_header .top_menu .container {
    width: 100%;
  }
  .hpage .v2_header .top_menu .container .row [class*="col-"] {
    width: 90%;
    float: none;
    margin: 0 auto;
    text-align: center;
  }
  .hpage .v2_header .top_menu .li_lg {
    margin-left: 20px;
    margin-right: 25px;
  }
  .hpage .appointment .form_ label {
    width: 100%!important;
    margin-right: 0!important;
  }
  .hpage_3 .home_featured .name_ {
    font-size: 22px;
  }
  .hpage_3 .subscribe .box_left .mail {
    margin-left: 0;
  }
  .hpage .home_featured .name_ {
    font-size: 20px;
  }
  .hpage .home_search_class .box_right:after {
    margin-left: -13px;
  }
  .hpage .home_search_class .box_right:before {
    margin-left: -11px;
  }
  .hpage .home_event .classes_it .box_img {
    min-height: 275px;
  }
  .hpage .home_event .classes_it .box_suma .btn_readmore {
    bottom: 0;
  }
  .hpage .home_event .classes_it .box_suma .name_ {
    font-size: 20px;
  }
  .hpage .home_event .classes_it .box_suma .date_ span {
    font-size: 14px;
  }
  .hpage .home_event_gallery .name_ {
    font-size: 20px;
  }
  .hpage .spt .item_spt {
    height: auto;
    padding: 15px;
  }
  .hpage .spt .add_ {
    float: right;
    margin-left: inherit;
  }
  .hpage .spt .add_ h3 {
    font-size: 18px;
  }
  .hpage .spt .add_ p {
    font-size: 13px;
  }
  .hpage .subscribe .container {
    width: 100%;
  }
  .main_sl {
    margin-bottom: 50px;
  }
  .main_sl .box_sliders:before {
    content: none;
  }
  .main_sl .box_sliders:after {
    content: none;
  }
  .about_welcome .img_ {
    width: 50%;
    top: 200px;
  }
  .about_demo .right_ .title_l h3 {
    font-size: 25px;
  }
  .about_demo .right_ .title_l h4 {
    font-size: 20px;
  }
  .about_demo .right_ .carousel_ .element_ dd {
    width: 80%;
  }
  .about_demo .right_ .bx-wrapper .bx-viewport {
    min-height: 225px;
  }
  .about_build .left_ .title_l h3 {
    font-size: 30px;
  }
  .about_build .left_ .title_l h4 {
    font-size: 25px;
  }
  .about_pl_grow .title_ {
    top: -25px;
  }
  .about_pl_grow .pl_grow_video {
    top: -185px;
  }
  .page_class_single .classes_related .box_pro .box_img .pro_img {
    height: 100%;
  }
  .page_class_single .classes_related .box_pro .sum {
    line-height: 24px;
  }
  .comingsoon .box_cd #countdown li {
    margin: 0 20px;
  }
  .page_blog .sidebar .new_post .tab_content .item_post_ .box_img {
    height: auto;
  }
  .page_blog .sidebar .social_ li {
    margin-bottom: 15px;
  }
  .page_blog .blog_single_content .content_view .txt .box_img {
    width: 100%;
  }
  .page_blog .blog_single_content .content_view .txt .box_img img {
    height: auto;
  }
  .page_blog .blog_single_content .content_view .txt .text {
    width: 100%;
    padding-left: 0;
  }
  .page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .user_ava {
    width: 11.47%;
  }
  .page_blog .blog_single_content .content_view .box_comments .comments_.do_post_ .box_content_cmt {
    width: 88.53%;
  }
  .page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .user_ava {
    width: 12.633%;
  }
  .page_blog .blog_single_content .content_view .box_comments .comments_.do_reply_ .box_content_cmt {
    width: 87.367%;
  }
  .page_blog .blog_single_content .content_view .levae_cmt .req {
    width: 100%!important;
    margin-left: 0!important;
  }
  .event_main_view .box_img img {
    height: 100%;
    transform: scale(1.2, 1);
    -webkit-transform: scale(1.2, 1);
    -moz-transform: scale(1.2, 1);
  }
  .event_detail .top_fly .fly_calendar .fly_form .btn_ {
    padding-left: 0;
  }
  .event_detail .top_fly .fly_calendar .fly_form .box_ {
    width: 200px;
  }
}
@media (min-width: 1081px) {
  .hpage_2 .top_box {
    position: relative;
    right: inherit;
    margin: 0 auto;
    width: 930px;
  }
  .hpage_2 .top_box.flw {
    float: none;
  }
}
@media (min-width: 993px) {
  #ht_header.hd_sub {
    height: auto;
  }
  #ht_header.hd_sub .nav-dropdown {
    padding-top: 37px;
  }
  .hd_sub [data-uk-sticky].uk-active .nav-dropdown {
    padding-top: 13px!important;
  }
}
@media (max-width: 991px) {
  #ht_header {
    height: auto!important;
  }
  .v2_header [data-uk-sticky].uk-active .top_menu {
    padding-top: 0!important;
    padding-top: 0;
  }
  .v2_header [data-uk-sticky].uk-active .top_menu .calendar {
    top: 0;
  }
  .v2_header [data-uk-sticky].uk-active .top_menu .nav-toggle {
    top: 1.5px;
  }
  .hpage .v2_header .top_menu {
    padding-top: 47px!important;
  }
  [data-uk-sticky].uk-active .top_menu .nav .nav-container {
    top: 15px;
  }
  [data-uk-sticky].uk-active .top_menu .nav-toggle {
    top: -7px;
  }
  [data-uk-sticky].uk-active .top_menu .appoint {
    top: 0;
  }
  .nav-dropdown .menu-item {
    border-color: #ffffff !important;
  }
  .has-dropdown:after {
    color: #ffffff;
  }
  .has-dropdown.is-active > .nav-dropdown {
    border-top: 1px dashed #ffffff;
  }
  .has-dropdown.is-active > .nav-dropdown .menu-item {
    padding-right: 20px;
  }
  .asp:after {
    color: #0567FA;
  }
  .asp > .nav-dropdown {
    background: #ffffff;
    border-top: 1px dashed #0567FA !important;
  }
  .asp > .nav-dropdown .menu-item {
    padding-left: 20px;
    background: #ffffff;
    border-bottom: 1px dashed #0567FA !important;
  }
  .asp > .nav-dropdown .menu-item:last-of-type {
    border-bottom: 0!important;
  }
  .asp > .nav-dropdown .menu-item .menu-link {
    color: #0567FA;
  }
  .nav-container.is-visible {
    background: #0567FA;
  }
  .nav-container.is-visible .menu-item {
    border-color: #ffffff;
  }
  .nav-container.is-visible .menu-item .menu-link.set_active {
    background: #ffffff;
    color: #0567FA;
  }
  .box_parallax {
    display: none;
  }
  .testim_title {
    text-align: center;
  }
  .event_title {
    text-align: center;
  }
  .top_section .top_box {
    width: 100%!important;
  }
  .top_menu .appoint {
    font-weight: 400;
    margin-right: 75px;
  }
  .top_menu .nav {
    left: 0;
  }
  .top_menu .nav .nav-container {
    position: relative;
    top: 30px;
    overflow: hidden;
  }
  .top_menu.smaller .nav .nav-container {
    top: 15px;
  }
  .top_menu.smaller .nav .nav-toggle {
    top: -7.5px;
  }
  ._section_item ._box_item {
    background-size: 100%!important;
    border-radius: 0!important;
  }
  ._section_item ._box_item:hover {
    border-radius: 0!important;
  }
  ._section_item ._box_item:hover:before {
    border-radius: 0!important;
  }
  ._section_featured {
    padding-bottom: 30px!important;
  }
  ._section_teacher {
    height: auto!important;
    background: url(../images/slide2.jpg) no-repeat;
    background-size: cover;
  }
  ._section_teacher:after {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    bottom: 0;
    right: 0;
    background: rgba(0, 0, 0, 0.81);
    z-index: 1;
  }
  ._section_teacher .box_teacher .row {
    clear: both;
  }
  ._section_teacher .box_teacher .box_item .teacher_info {
    background-size: inherit!important;
  }
  ._section_teacher .box_teacher .box_item .teacher_info a {
    margin-top: 40px!important;
  }
  ._section_teacher .container {
    position: relative;
    z-index: 5;
  }
  ._section_gallery .gallery_content .element-item {
    width: 48.7175%!important;
  }
  ._section_counter {
    height: auto!important;
    padding: 30px 0!important;
  }
  ._section_testim {
    height: auto!important;
    background: url(../images/slide3.jpg) no-repeat;
    background-size: cover;
  }
  ._section_testim:after {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    bottom: 0;
    right: 0;
    background: rgba(160, 187, 134, 0.4);
    z-index: 1;
  }
  ._section_testim .container {
    position: relative;
    z-index: 5;
  }
  ._section_testim .testim_vd {
    margin-bottom: 50px;
  }
  ._section_testim .box_location {
    background-size: 100%!important;
  }
  ._section_event {
    height: auto!important;
    background: url(../images/slide4.jpg) no-repeat;
    background-size: cover;
  }
  ._section_event:after {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    bottom: 0;
    right: 0;
    background: rgba(160, 187, 134, 0.4);
    z-index: 1;
  }
  ._section_event .container {
    position: relative;
    z-index: 5;
  }
  .ht_footer .footer_ {
    padding-bottom: 50px;
  }
  .ht_footer .footer_ .box_register {
    background: url(../images/bg_reg.png) repeat;
    padding: 20px;
    min-height: inherit;
    margin-top: -35px;
  }
  .ht_footer .footer_ .box_register span {
    font-size: 16px;
  }
  .ht_footer .footer_ .box_register .btn_reg {
    font-size: 12px;
    width: 150px;
    height: 30px;
    line-height: 30px;
  }
  .ht_footer .footer_ .footer_main .uselink li a {
    display: block;
    width: 100%;
  }
  .ht_footer .footer_ .footer_main .des_:after {
    border: none;
  }
  .ht_footer .footer_ .footer_main .des_ img {
    border: 3px solid rgba(107, 162, 173, 0.72);
  }
  .hpage [data-uk-sticky].uk-active .top_menu .nav .nav-container {
    top: 7px;
  }
  .hpage .v2_header .top_menu {
    padding-top: 50px;
    height: 140px;
  }
  .hpage .v2_header .top_menu .nav-toggle {
    top: 14.5px;
  }
  .hpage .v2_header .top_menu .nav {
    margin-top: 5px;
  }
  .hpage .v2_header .top_menu .nav .nav-container {
    top: 63px;
  }
  .hpage .v2_header .top_menu .lg.lg_none {
    display: block;
    top: 0;
  }
  .hpage .v2_header .top_menu .li_lg {
    display: none;
  }
  .hpage .v2_header .top_menu .calendar {
    top: 13px;
    margin-right: 60px;
  }
  .hpage .appointment .box_bear {
    position: static;
    width: 100%;
    text-align: center;
  }
  .hpage .appointment .box_bear img {
    max-width: 100%;
  }
  .hpage .home_pricing .item_pr {
    margin-bottom: 50px;
  }
  .hpage .home_search_class .left_ {
    position: static;
    width: 100%;
    float: left;
  }
  .hpage .home_search_class .right_ {
    position: static;
    width: 100%;
    float: left;
  }
  .hpage .home_event .classes_it .box_img:after {
    height: 200px;
  }
  .hpage .home_event .classes_it .box_img:before {
    height: 50px;
  }
  .hpage .ht_footer .footer_ .box_register {
    border-radius: 150px;
  }
  .hpage .ht_footer .footer_ .footer_main .uselink li a {
    display: block;
    width: 100%;
  }
  .hpage .subscribe .form_sub {
    margin-top: 50px;
  }
  .hpage .appointment .title_l {
    text-align: center;
  }
  .hpage .appointment .form_ button {
    display: block;
    margin: 0 auto;
  }
  .hpage .home_event .classes_it .box_suma .btn_readmore {
    bottom: 30px;
  }
  .hpage .home_event_gallery .item_eg {
    width: 100%;
  }
  .hpage .home_event_gallery .shape {
    display: none;
  }
  .hpage .loca_ .title {
    left: 50%;
    margin-left: -130.5px;
    margin-bottom: 50px;
  }
  .hpage .spt .add_ {
    float: left;
    margin-left: 3.71%;
  }
  .hpage .home_pricing .title_ p {
    padding: 0 15px;
  }
  .hpage .home_pricing .item_main .icon_bug {
    margin-bottom: 20px!important;
  }
  .hpage .home_pricing .item_main .dot_ dd {
    margin: 10px 0;
  }
  .about_welcome .img_ {
    width: 100%;
    position: static;
    margin: 50px 0;
  }
  .about_services .item_sv {
    margin-bottom: 50px;
  }
  .about_demo .right_ {
    border-radius: 0;
  }
  .about_demo .right_ .title_l h3 {
    font-size: 30px;
  }
  .about_demo .right_ .bx-controls {
    top: inherit;
  }
  .about_demo .pr_0 {
    padding-left: inherit;
  }
  .about_demo .pl_0 {
    padding-right: inherit;
  }
  .about_build .left_ {
    margin-bottom: 50px;
  }
  .about_pl_grow {
    height: auto;
  }
  .about_pl_grow .title_ {
    top: 0;
  }
  .about_pl_grow .item_midde {
    top: 0;
  }
  .about_pl_grow .item_midde .pl_grow_video {
    top: 60%;
    position: absolute;
    left: 50%;
    margin-left: -37.5px;
  }
  .classes_enroll .top_enroll {
    height: auto;
    padding-bottom: 20px;
  }
  .classes_enroll .top_enroll .left_ {
    margin-top: 40px;
  }
  .classes_enroll .top_enroll .left_ h1{
    font-size: 26px;
  }
  .classes_enroll .top_enroll .right_ .spt {
    margin-top: 75px;
  }
  .classes_enroll .top_enroll .right_ .bub {
    margin-top: 20px;
  }
  .classes_enroll .title_sort {
    height: auto;
    padding-bottom: 20px;
  }
  .classes_enroll .navigation {
    float: left;
  }
  .classes_enroll .navigation li {
    margin-left: 0;
    margin-right: 10px;
  }
  .page_class_single .classes_related .box_pro .item_pro {
    width: 48.5%;
    margin-right: 3%;
    margin-bottom: 40px;
  }
  .page_class_single .classes_related .box_pro .item_pro:nth-of-type(2n) {
    margin-right: 0;
  }
  .page_class_single .sidebar {
    margin-top: 50px;
  }
  .page_class_single .leftview_2 .letter .content_r {
    width: 100%;
  }
  .page_class_single .leftview_2 .letter .content {
    width: 100%;
  }
  .page_404 .oops {
    margin: 50px 0;
  }
  .page_404 .box_img {
    top: 0;
    right: 0;
    text-align: center;
  }
  .comingsoon {
    height: auto;
    padding-bottom: 50px;
    background-size: cover;
  }
  .comingsoon .box_cd #countdown li {
    margin: 0 auto 30px auto;
    display: block;
    padding-top: 1px;
  }
  .comingsoon .box_cd #countdown li span {
    display: block;
  }
  .contact_page .box_info {
    margin-top: 50px;
  }
  .event_main_view .list_ {
    height: auto;
  }
  .event_main_view .list_ .box_img {
    width: 100%;
  }
  .event_main_view .list_ .box_img img {
    width: 100%;
    height: 100%;
    transform: scale(1.2, 1);
    -webkit-transform: scale(1.2, 1);
    -moz-transform: scale(1.2, 1);
  }
  .event_main_view .list_ .box_sumary_ {
    width: 100%;
    padding: 30px;
  }
  .event_detail .top_fly {
    height: auto;
  }
  .event_detail .top_fly .fly_carousel {
    width: 100%;
  }
  .event_detail .top_fly .fly_calendar {
    margin-top: 30px;
    width: 100%;
  }
  .event_detail .top_fly .fly_calendar .fly_form .btn_ {
    text-align: center;
  }
  .event_detail .top_fly .fly_calendar .fly_form .box_ {
    width: 100%;
    margin-right: 0;
  }
  .event_detail .classes_related .box_pro .item_pro {
    width: 48.5%;
    margin-right: 3%;
    margin-bottom: 40px;
  }
  .event_detail .classes_related .box_pro .item_pro:nth-of-type(2n) {
    margin-right: 0;
  }
  .page_blog .post_ .box_link h3 {
    font-size: 30px;
    line-height: 30px;
  }
}
@media (max-width: 1080px) {
  .top_section .top_box {
    height: auto;
    padding: 0 15px;
    width: 100%;
    background: #333;
  }
  .top_section .top_box .top_list li {
    margin-bottom: 5px;
  }
  .top_section .top_box .top_list li.spc:after {
    display: none;
  }
  .top_menu .lg {
    top: 63.5px;
    width: 150px;
    height: 80px;
  }
  .hpage .v2_header .top_menu {
    padding-top: 94px;
  }
}
@media (max-width: 768px) {
  .main_sl .box_sliders .tit_main {
    min-height: inherit!important;
    border: 0!important;
  }
  .main_sl .box_sliders .tit_main:before {
    content: none;
  }
  .main_sl .box_sliders .tit_main:after {
    content: none;
  }
  .main_sl .box_sliders .welcome_ .big_1 {
    font-size: 20px;
  }
  .main_sl .box_sliders .welcome_ .big_2 {
    font-size: 15px;
  }
  .main_sl .box_sliders .welcome_ .big_3 {
    font-size: 15px;
  }
  .hpage .ht_footer .footer_:before {
    border-radius: 0;
  }
  .hpage .ht_footer .footer_ .box_register {
    min-height: 80px;
    padding: 25px 30px;
    border-radius: 0;
    width: 100%;
    position: absolute;
    left: 0;
  }
  .hpage .ht_footer .footer_ .box_register span {
    font-size: 16px;
  }
  .hpage .ht_footer .footer_ .box_register a {
    font-size: 13px;
    width: 140px;
    height: 30px;
    line-height: 30px;
  }
  .contact_page .box_mes .form_ .required {
    width: 100%;
    margin-right: 0;
  }
  .page_class_single .gallery #slider .flex-viewport {
    height: auto;
  }
  .page_class_single .classes_related .box_pro .item_pro {
    width: 100%;
    margin-right: 0;
  }
  .event_detail .about_event .left_ {
    width: 100%;
    padding-right: 30px;
  }
  .event_detail .about_event .box_video {
    width: 100%;
    margin-bottom: 30px;
  }
  .event_detail .about_event .box_video img {
    width: 100%;
  }
  .event_detail .classes_related .box_pro .item_pro {
    width: 100%;
    margin-right: 0;
  }
  .about_services {
    padding-bottom: 0;
  }
}
@media (max-width: 720px) {
  .top_section .top_box .top_list li {
    float: left;
    width: 100%;
  }
  .top_section .top_box .top_list form button[type="submit"] {
    right: 4px;
  }
  .top_section .top_box .top_social {
    margin-top: 0;
    margin-bottom: 10px;
    float: left;
    width: 100%;
    margin-right: 7px;
    margin-left: 0;
  }
  .top_menu {
    height: 170px;
    padding-top: 118px;
  }
  .top_menu .nav .nav-container {
    top: 22px;
  }
  .top_menu .lg {
    top: 115px;
    width: 94px;
    height: 50px;
  }
  .top_menu .appoint {
    height: 30px;
    width: 130px;
    line-height: 30px;
    top: 6px;
  }
  .hpage .v2_header .top_menu {
    padding-top: 120px!important;
    height: 190px;
  }
  .hpage .v2_header .top_menu .nav .nav-container {
    top: 22px;
  }
  .hpage .v2_header .top_menu .calendar {
    top: 2px;
  }
  .hpage .v2_header .top_menu .nav-toggle {
    top: 3.5px;
  }
  .hpage .home_event .classes_it .box_img:after {
    background: none;
  }
}
@media (max-device-width: 1024px) and (orientation: landscape) {
  .parallax {
    display: none;
  }
}
@media (max-width: 680px) {
  .about_build .right_ .item_cter {
    width: 100%;
    margin-right: 0;
  }
  .event_detail .event_ .tt_ {
    white-space: inherit;
  }
  .event_detail .top_fly .fly_calendar .fly_form .btn_ li {
    width: 100%;
    text-align: center;
    margin: 0;
    margin-bottom: 15px;
  }
  .page_blog .post_ .name_ .btn_name {
    font-size: 24px;
  }
  .page_blog .post_ .box_link h3 {
    font-size: 18px;
    line-height: 24px;
  }
}
@media (max-width: 568px) {
  h1,
  h2,
  h3,
  h4,
  h5,
  h6,
  a {
    white-space: inherit!important;
  }
  .category_ .left_ {
    width: 100%;
  }
  .hpage .appointment .box_bear {
    padding: 0;
  }
  .hpage .subscribe .box_left .left_form {
    margin-top: 30px;
  }
  .hpage .subscribe .box_left .left_form dt {
    margin-bottom: 10px;
  }
  .page_class_single {
    padding-bottom: 50px;
  }
  .page_class_single .leftview .letter .content .quote {
    height: auto;
    padding: 20px;
  }
  .page_class_single .leftview .letter .content .quote h3 {
    white-space: inherit;
    line-height: 30px;
  }
  .page_class_single .leftview .letter .shape_lt {
    position: static;
    float: left;
    margin-bottom: 20px;
  }
  .page_class_single .leftview .letter .name_ h3 {
    font-size: 24px;
    white-space: inherit;
  }
  .classes_enroll {
    padding-bottom: 50px;
  }
  .classes_enroll .top_enroll .left_ h1{
    font-size: 24px;
    white-space: inherit;
    line-height: 30px;
  }
  .navigation li {
    margin-bottom: 10px;
  }
  .title_l h3,
  .title_ h3,
  .gallery_title h3,
  .class_title h3 {
    white-space: inherit;
  }
  .title_l h4,
  .title_ h4,
  .gallery_title h4,
  .class_title h4 {
    white-space: inherit;
  }
  .flex-direction-nav a {
    z-index: 2;
  }
  .acc_head {
    font-size: 13px;
    text-transform: none;
    overflow: hidden;
    padding-right: 30px;
  }
  .page_class_single .leftview_2 .letter .btn_enroll_r {
    position: static;
    float: left;
    width: 100%;
    margin-bottom: 20px;
  }
  .event_main_view .name_ {
    font-size: 24px;
  }
  .event_detail .top_fly .fly_calendar .name_ {
    font-size: 30px;
    line-height: 36px;
  }
  .oops h4 {
    white-space: inherit;
  }
  .page_blog .post_ .list_if li {
    margin-bottom: 15px;
  }
  .category_ .right_ {
    float: left;
    width: 100%;
    margin-top: 10px;
    padding-top: 0;
  }
  .comingsoon .title_ h3 {
    font-size: 40px;
  }
  .comingsoon .form_ {
    width: 100%;
  }
  .gutter-sizer {
    width: 0!important;
  }
  ._section_gallery {
    padding-bottom: 0!important;
  }
  ._section_gallery .gallery_nav button {
    margin-bottom: 10px;
  }
  ._section_gallery .gallery_content .element-item {
    width: 100%!important;
  }
  ._section_gallery .gallery_content .element-item .gallery_item {
    width: 100%;
  }
  .ht_footer .footer_ .footer_main .des_ {
    width: 100%;
  }
  .ht_footer .footer_ .footer_main .des_ img {
    width: 100%;
  }
  .ht_footer .footer_ .box_register .btn_reg {
    margin-top: 20px;
  }
  ._section_question {
    min-height: inherit!important;
    height: auto;
    padding-bottom: 100px!important;
  }
  ._section_question .q_title h3 {
    font-size: 24px!important;
  }
  .testim_title h3 {
    font-size: 30px!important;
  }
  .testim_title h4 {
    font-size: 24px!important;
  }
  .teacher_title h2 {
    font-size: 30px!important;
  }
  .teacher_title h3 {
    font-size: 24px!important;
  }
  ._section_classes {
    padding-bottom: 40px!important;
    padding-top: 40px!important;
  }
  ._section_item ._box_item {
    background-size: cover!important;
  }
  ._section_item ._box_item .medal_ h3 {
    margin-top: 10px;
  }
  .title_l h3,
  .title_ h3,
  .gallery_title h3,
  .class_title h3 {
    font-size: 30px!important;
  }
  .title_l h4,
  .title_ h4,
  .gallery_title h4,
  .class_title h4 {
    font-size: 24px!important;
  }
  .hpage .ht_footer .footer_ .box_register {
    position: static;
  }
  .hpage ._section_question {
    padding-top: 0;
  }
  .hpage .home_event {
    padding-bottom: 100px;
  }
  ._section_testim .testim_vd {
    height: auto!important;
    padding-bottom: 50px!important;
  }
  ._section_testim .box_location {
    background: none!important;
  }
  ._section_testim .box_location .location_ {
    padding: 30px!important;
  }
  ._section_testim .box_location .location_ li:last-of-type a {
    bottom: 30px;
    font-size: 14px;
  }
}
@media (max-width: 900px) {
  .main_sl .box_sliders .icon_ {
    display: none;
  }
}
@media (max-width: 800px) {
  .top_menu .appoint {
    margin-right: 55px;
    width: 125px;
  }
  ._section_testim .testim_vd p {
    max-width: 100%!important;
  }
  ._section_event .bx-wrapper .bx-viewport {
    height: auto!important;
  }
  ._section_event .box_event .event_cs .event_item {
    height: auto!important;
    padding-bottom: 50px!important;
  }
  ._section_event .box_event .event_cs .event_item .event_content {
    padding-top: 15px!important;
    padding-bottom: 50px!important;
    height: auto!important;
  }
  ._section_event .box_event .event_cs .event_item .event_content dl {
    margin-top: 10px;
  }
  ._section_event .box_event .event_cs .event_item .event_content dl dt {
    width: 100%!important;
    margin-bottom: 5px;
  }
  ._section_event .box_event .event_cs .event_item .event_content dl dd {
    width: 100%!important;
  }
  ._section_event .box_event .event_cs .event_item .event_content h3 a {
    font-size: 24px!important;
  }
  ._section_event .box_event .event_cs .event_item .event_content > a {
    bottom: 20px!important;
  }
  ._section_event .event_title h3 {
    font-size: 24px!important;
  }
  ._section_event .event_title h4 {
    font-size: 20px!important;
  }
}
@font-face {
  font-family: kinder;
  src: url(../fonts/kinder.woff), url(../fonts/kinder.ttf), url(../fonts/kinder.svg), url(../fonts/kinder.eot);
}
/***************************Style***************************/
.cl {
  clear: both;
}
.flw {
  float: left;
  width: 100%;
}
.parallax {
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 2;
  position: static;
}
.parallax img {
  display: none;
  position: absolute;
  left: 50%;
  bottom: 0;
  min-width: 100%;
  min-height: 100%;
  -webkit-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0);
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
}
/***********************  MAIN  **************************/
.nopadding {
  padding: 0;
}
.box_shadow {
  box-shadow: 0 5px 30px #e4e4e4;
  margin-bottom: 50px;
  border-radius: 15px;
}
.page_content {
  float: left;
  width: 100%;
}
._section_item {
  position: relative;
  z-index: 2;
}
._section_item ._box_item {
  float: right;
  width: 100%;
  padding: 52px 36px;
  min-height: 200px;
  position: relative;
}
._section_item ._box_item:hover:before {
  opacity: 1;
  transition-duration: 0.3s;
}
._section_item ._box_item:before {
  content: "";
  transition-duration: 0.3s;
  opacity: 0;
}
._section_item ._box_item._box_item_one {
  background: #ffffff url(../images/programming-featured-cover.png) no-repeat top left;
}
._section_item ._box_item._box_item_two {
  background: #ffffff url(../images/programming-featured-cover.png) no-repeat top left;
}
._section_item ._box_item._box_item_three {
  background: #ffffff url(../images/part3.png) no-repeat top left;
}
._section_item ._box_item.bd_radi_l {
  border-radius: 15px 0 0 15px;
}
._section_item ._box_item.bd_radi_l:hover:before {
  border-radius: 15px 0 0 15px;
  content: "";
  background: rgba(0, 134, 255, 0.3);	
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 0;
}
._section_item ._box_item.bd_radi_r {
  border-radius: 0 15px 15px 0;
}
._section_item ._box_item.bd_radi_r:hover:before {
  border-radius: 0 15px 15px 0;
  content: "";
  background: rgba(0, 134, 255, 0.3);	
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 0;
}
._section_item ._box_item:hover:before {
  content: "";
  background: rgba(0, 134, 255, 0.3);	
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 0;
}
._section_item ._box_item:hover .kinder_icon:before {
  color: #ffffff;
  transition-duration: 0.3s;
}
._section_item ._box_item:hover .btn_read {
  transition-duration: 0.3s;
  border-color: #ffffff;
  color: #ffffff;
}
._section_item ._box_item:hover .medal_ span {
  color: #ffffff;
  transition-duration: 0.3s;
}
._section_item ._box_item:hover .medal_ h3 {
  color: #ffffff;
  transition-duration: 0.3s;
}
._section_item ._box_item:hover .medal_ p {
  color: #ffffff;
  transition-duration: 0.3s;
}
._section_item ._box_item .medal_ {
  float: center;
  width: 100%;
  margin-top: 23px;
  position: relative;
  z-index: 1;
}
._section_item ._box_item .medal_ span {
font-family: 'Tajawal', sans-serif;  font-size: 24px;
  font-weight: 300;
  color: #303030;
  transition-duration: 0.3s;
}
._section_item ._box_item .medal_ h3 {
  font-size: 36px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  transition-duration: 0.3s;
  color: #303030;
  margin-bottom: 23px;
  white-space: nowrap;
}
._section_item ._box_item .medal_ p {
  color: #777;
  margin-bottom: 0;
  transition-duration: 0.3s;
  line-height: 24px;
}
._section_item ._box_item .btn_read {
  text-transform: uppercase;
  color: #0567FA;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  width: 130px;
  height: 40px;
  text-align: center;
  line-height: 38px;
  display: block;
  border-radius: 50px;
  border: 1px solid #0567FA;
  position: absolute;
  left: 36px;
  bottom: 50px;
}
._section_item ._box_item .btn_read:hover {
  -webkit-box-shadow: 0px 0px 10px 0px #ffffff;
  -moz-box-shadow: 0px 0px 10px 0px #ffffff;
  box-shadow: 0px 0px 10px 0px #ffffff;
}
._section_item .icon-1:before {
  content: "\e900";
}
._section_item .icon-2:before {
  content: "\e901";
}
._section_item .icon-3:before {
  content: "\e902";
}
._section_item .kinder_icon {
  position: relative;
  z-index: 5;
}
._section_item .kinder_icon:before {
  color: #cccccc;
  font-family: 'kinder' !important;
  speak: none;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;
  font-size: 72px;
  /* Better Font Rendering =========== */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
._section_featured {
  padding-bottom: 110px;
}
._section_featured .row {
  margin-bottom: 30px;
}
._section_featured ._fl {
  width: 78px;
  height: 81px;
  display: block;
  background: url(../images/fl.png) no-repeat top center;
  text-align: center;
  line-height: 85px;
  margin-bottom: 30px;
}
._section_featured ._fl:before {
  color: #ffffff;
  font-size: 24px;
}
._section_featured ._it_feat {
  margin-bottom: 30px;
}
._section_featured ._it_feat h3 {
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  font-size: 24px;
  color: #303030;
  position: relative;
  padding-bottom: 20px;
  margin-bottom: 25px;
  white-space: nowrap;
}
._section_featured ._it_feat h3:after {
  content: "";
  background: #eeeeee;
  width: 30px;
  height: 1px;
  position: absolute;
  bottom: 0;
  left: 0;
}
._section_featured ._it_feat h3 span {
  font-weight: 300;
}
._section_featured ._it_feat p {
  font-size: 14px;
  color: #777;
  line-height: 22px;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  /* Safari 5+ ONLY */
  ::i-block-chrome,
  .wave {
    height: 12px!important;
    background: url(../images/wave.png) repeat-x;
  }
  ::i-block-chrome,
  .classes_it .box_img img {
    -webkit-transform: scale(1) !important;
  }
}
.background_more {
  background: #0567FA !important;
}
._section_classes {
  background: #f8f8f8;
  padding-top: 110px;
  padding-bottom: 140px;
}
._section_classes .class_title {
  text-align: center;
  margin-bottom: 70px;
}
._section_classes .class_title h3 {
  font-size: 48px;
  color: #303030;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  margin-bottom: 15px;
}
._section_classes .class_title h4 {
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  font-size: 36px;
  color: #0567FA;
}
._section_classes .classes_it {
  margin-bottom: 71px;
  border-radius: 20px;
  border-right-color: transparent;
  transition-duration: 0.4s;
  -webkit-transition-duration: 0.4s;
  -moz-transition-duration: 0.4s;
}
._section_classes .classes_it:hover {
  -webkit-box-shadow: 0px 0px 7px 0px rgba(0, 0, 0, 0.1);
  -moz-box-shadow: 0px 0px 7px 0px rgba(0, 0, 0, 0.1);
  box-shadow: 0px 0px 7px 0px rgba(0, 0, 0, 0.1);
  border-right-color: transparent;
  transition-duration: 0.4s;
  -webkit-transition-duration: 0.4s;
  -moz-transition-duration: 0.4s;
}
._section_classes .classes_it:hover .box_suma {
  background: #f8f8f8;
  border-left-color: transparent;
}
._section_classes .classes_it:hover .box_img .wave:before {
  background-image: radial-gradient(circle at 10px -5px, transparent 14px, #f8f8f8 16px);
}
._section_classes .classes_it:hover .box_img .wave:after {
  background-image: radial-gradient(circle at 10px 15px, #f8f8f8 12px, transparent 13px);
}
._section_classes .classes_it .box_img {
  position: relative;
  width: 100%;
  overflow: hidden;
  z-index: 2;
  border-radius: 20px 20px 0 0;
}
._section_classes .classes_it .box_img:hover img {
  transform: scale(1);
  opacity: 0.75;
  -webkit-transform: scale(1);
  -moz-transform: scale(1);
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
._section_classes .classes_it .box_img img {
  transform: scale(1.1);
  -webkit-transform: scale(1.1);
  -moz-transform: scale(1.1);
  border-radius: 15px 15px 0 0;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
  width: 100%;
}
._section_classes .classes_it .box_img .wave {
  position: absolute;
  width: 100%;
  left: 0;
  bottom: 0;
  height: 0;
}
._section_classes .classes_it .box_img .wave:before {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  right: 0;
  background-repeat: repeat;
  height: 12px;
  background-size: 20px 20px;
  background-image: radial-gradient(circle at 10px -5px, transparent 14px, #ffffff 16px);
}
._section_classes .classes_it .box_img .wave:after {
  content: "";
  position: absolute;
  left: 0;
  bottom: 0;
  right: 0;
  background-repeat: repeat;
  height: 12px;
  background-size: 40px 20px;
  background-image: radial-gradient(circle at 10px 15px, #ffffff 12px, transparent 13px);
}
._section_classes .classes_it .box_suma {
  border: 1px solid #eeeeee;
  border-top: 0;
  height: 349px;
  margin-top: -15px;
  padding: 30px 30px 39px 30px;
  border-radius: 0 0 20px 20px;
  position: relative;
  background: #ffffff;
}
._section_classes .classes_it .box_suma .date_ {
  margin-bottom: 7px;
}
._section_classes .classes_it .box_suma .date_ span {
  float: left;
  font-size: 18px;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  color: #777;
  margin-right: 20px;
}
._section_classes .classes_it .box_suma .name_ {
  font-size: 30px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  line-height: 1;
  color: #303030;
  white-space: nowrap;
}
._section_classes .classes_it .box_suma .name_:hover {
  color: #0567FA;
}
._section_classes .classes_it .box_suma .rate_ {
  margin-top: 15px;
}
._section_classes .classes_it .box_suma .rate_ span {
  color: #0567FA;
  font-size: 18px;
}
._section_classes .classes_it .box_suma .sumary_ {
  margin-top: 10px;
}
._section_classes .classes_it .box_suma .sumary_ p {
  font-size: 14px;
  color: #303030;
  line-height: 24px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
}
._section_classes .classes_it .box_suma .btn_apply {
  text-transform: uppercase;
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  color: #ffffff;
  background: #0567FA;
  width: 144px;
  height: 40px;
  line-height: 40px;
  position: absolute;
  left: 30px;
  bottom: 39px;
  text-align: center;
  border-radius: 20px;
  text-indent: -13px;
  overflow: hidden;
}
._section_classes .classes_it .box_suma .btn_apply:before {
  right: 10px;
  opacity: 0;
  font-family: "ionicons";
  position: relative;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
  content: "\f38e";
}
._section_classes .classes_it .box_suma .btn_apply:hover {
  background: #cc591c;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
  text-indent: 7.5px;
}
._section_classes .classes_it .box_suma .btn_apply:hover:before {
  content: "\f38e";
  right: 7px;
  opacity: 1;
  font-family: "ionicons";
  position: relative;
}
._section_classes .classes_it .box_suma .more_ {
  position: absolute;
  right: 30px;
  bottom: 46.5px;
  height: 25px;
  width: 25px;
  border: 0;
  background: transparent;
  cursor: pointer;
  display: block;
  overflow: hidden;
  padding: 0;
}
._section_classes .classes_it .box_suma .more_:active span {
  background: #0567FA;
}
._section_classes .classes_it .box_suma .more_:hover span {
  background: #0567FA;
}
._section_classes .classes_it .box_suma .more_:hover + .popup_ {
  visibility: visible;
  bottom: 18px;
  opacity: 1;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
._section_classes .classes_it .box_suma .more_ span {
  width: 5px;
  height: 5px;
  border-radius: 50%;
  display: inline-block;
  background: #cccccc;
}
._section_classes .classes_it .box_suma .popup_ {
  position: absolute;
  right: 5px;
  bottom: 10px;
  border-radius: 20px;
  text-align: center;
  visibility: hidden;
  width: 78px;
  height: 28px;
  border: 1px solid #aaaaaa;
  line-height: 21px;
  opacity: 0;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
._section_classes .classes_it .box_suma .popup_:hover {
  visibility: visible;
  bottom: 18px;
  opacity: 1;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
._section_classes .classes_it .box_suma .popup_:after,
._section_classes .classes_it .box_suma .popup_:before {
  bottom: 100%;
  left: 50%;
  border: solid transparent;
  content: " ";
  height: 0;
  width: 0;
  position: absolute;
  pointer-events: none;
}
._section_classes .classes_it .box_suma .popup_:after {
  border-color: rgba(250, 250, 250, 0);
  border-bottom-color: #fafafa;
  border-width: 7.5px;
  margin-left: -7.5px;
}
._section_classes .classes_it .box_suma .popup_:before {
  border-color: rgba(170, 170, 170, 0);
  border-bottom-color: #aaaaaa;
  border-width: 8.5px;
  margin-left: -8.5px;
}
._section_classes .classes_it .box_suma .popup_ .btn_popup {
  font-size: 12px;
  color: #777;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
}
._section_classes .classes_it .box_suma .popup_ .btn_popup:hover {
  color: #0567FA;
}
._section_classes .all_classes {
  text-transform: uppercase;
  color: #0567FA;
  border: 1px solid #0567FA;
  height: 50px;
  width: 263px;
  text-align: center;
  border-radius: 25px;
  display: block;
  margin: 0 auto;
  font-weight: 700;
  font-size: 16px;
  line-height: 48px;
  position: relative;
}
._section_classes .all_classes:after {
  content: "\f38e";
  font-family: "ionicons";
  position: absolute;
  left: 80%;
  opacity: 0;
  color: #ffffff;
  transition-duration: 0.3s;
}
._section_classes .all_classes:hover {
  background: #0567FA;
  color: #ffffff;
}
._section_classes .all_classes:hover:after {
  opacity: 1;
  transition-duration: 0.3s;
}
._section_teacher {
  height: 760px;
  position: relative;
}
._section_teacher .box_parallax {
  position: absolute;
  height: 760px;
  overflow: hidden;
}
._section_teacher .box_parallax .parallax:before {
  content: "";
  background: rgba(0, 0, 0, 0.8);
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
}
._section_teacher .box_teacher {
  position: relative;
  z-index: 5;
  padding-top: 103px;
}
._section_teacher .box_teacher .teacher_title {
  text-align: center;
}
._section_teacher .box_teacher .teacher_title h2 {
  font-size: 48px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  color: #ffffff;
}
._section_teacher .box_teacher .teacher_title h3 {
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  font-size: 36px;
  color: #0567FA;
  margin-top: 13px;
  margin-bottom: 23px;
}
._section_teacher .box_teacher .teacher_title p {
  line-height: 24px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  font-size: 14px;
  color: #ffffff;
}
._section_teacher .box_teacher .box_item {
  text-align: center;
  position: relative;
  margin-top: 59px;
  padding-bottom: 43px;
  overflow: hidden;
}
._section_teacher .box_teacher .box_item:hover .social_ {
  right: 0;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
._section_teacher .box_teacher .box_item .social_ {
  z-index: 1;
  position: absolute;
  right: -25px;
  top: 18px;
  width: 25px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
._section_teacher .box_teacher .box_item .social_ li {
  float: left;
  width: 100%;
  cursor: pointer;
  text-align: right;
  margin-bottom: 20px;
}
._section_teacher .box_teacher .box_item .social_ a {
  font-size: 16px;
  color: #ffffff;
  float: left;
  width: 20px;
  height: 20px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
._section_teacher .box_teacher .box_item .social_ a:hover {
  color: #fc403b;
  margin-left: 5px;
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
._section_teacher .box_teacher .box_item .teacher_info {
  width: 269px;
  height: 128px;
  position: absolute;
  bottom: 0;
  left: 0;
  float: left;
  background: url(../images/plug.png) no-repeat top center;
}
._section_teacher .box_teacher .box_item .teacher_info a {
  font-size: 36px;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  color: #ffffff;
  display: block;
  margin-top: 35px;
}
._section_teacher .box_teacher .box_item .teacher_info span {
  background: url(../images/wa.png) no-repeat center center;
  display: block;
  height: 5px;
  position: relative;
  top: -5px;
}
._section_teacher .box_teacher .box_item .teacher_info p {
font-family: 'Tajawal', sans-serif;  font-size: 12px;
  color: #ffffff;
  font-weight: 400;
}
@-webkit-keyframes hvr_icon_push {
  50% {
    -webkit-transform: scale(0.9);
    transform: scale(0.9);
  }
}
@keyframes hvr_icon_push {
  50% {
    -webkit-transform: scale(0.9);
    transform: scale(0.9);
  }
}
.hvr_icon_push {
  -webkit-transform: translateZ(0);
  transform: translateZ(0);
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
  -moz-osx-font-smoothing: grayscale;
  padding-right: 2.2em;
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
}
.hvr_icon_push:hover {
  -webkit-animation-name: hvr_icon_push;
  animation-name: hvr_icon_push;
  -webkit-animation-duration: 0.3s;
  animation-duration: 0.3s;
  -webkit-animation-timing-function: linear;
  animation-timing-function: linear;
  -webkit-animation-iteration-count: 1;
  animation-iteration-count: 1;
}
._section_counter {
  height: 359px;
  background: #ffffff;
  padding: 110px 0;
}
._section_counter .item_counter {
  text-align: center;
}
._section_counter .item_counter .smile {
  margin-bottom: 20px;
}
._section_counter .item_counter .or_ {
  color: #0567FA;
}
._section_counter .item_counter .or_:after {
  content: url(../images/ct_or.png);
  width: 100%;
  display: block;
  line-height: 0;
}
._section_counter .item_counter .bl_ {
  color: #f10027;
}
._section_counter .item_counter .bl_:after {
  content: url(../images/ct_bl.png);
  width: 100%;
  display: block;
  line-height: 0;
}
._section_counter .item_counter .ort_ {
  color: #f2ad29;
}
._section_counter .item_counter .ort_:after {
  content: url(../images/ct_ort.png);
  width: 100%;
  display: block;
  line-height: 0;
}
._section_counter .item_counter .orr_ {
  color: #f25829;
}
._section_counter .item_counter .orr_:after {
  content: url(../images/ct_r.png);
  width: 100%;
  display: block;
  line-height: 0;
}
._section_counter .item_counter .counter {
  font-size: 48px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  line-height: 1;
  margin-bottom: 20px;
  display: block;
}
._section_counter .item_counter .counter.one {
  color: #0567FA;
}
._section_counter .item_counter .counter.one:after {
  content: "+";
  font-size: 30px;
  position: relative;
  top: -15px;
}
._section_counter .item_counter .counter.two {
  color: #f10027;
}
._section_counter .item_counter .counter.three {
  color: #568C1A;
}
._section_counter .item_counter .counter.three:after {
  content: "+";
  font-size: 30px;
  position: relative;
  top: -15px;
}
._section_counter .item_counter .counter.four {
  color: #336600;
}
._section_counter .item_counter p {
  font-size: 18px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  margin-top: 20px;
}
._section_testim {
  position: relative;
  padding-top: 140px;
  padding-bottom: 144px;
  height: 800px;
}
._section_testim .box_parallax {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  overflow: hidden;
  height: 800px;
}
._section_testim .box_parallax .parallax:before {
  content: "";
  background: rgba(48, 87, 0, 0.5);
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
}
._section_testim .container {
  position: relative;
  z-index: 5;
}
._section_testim .testim_title h3 {
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  font-size: 48px;
  color: #ffffff;
  margin-top: -7px;
  margin-bottom: 17px;
  white-space: nowrap;
}
._section_testim .testim_title h4 {
  font-size: 36px;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  color: #ffffff;
  margin-bottom: 23px;
  white-space: nowrap;
}
._section_testim .testim_title p {
  font-size: 14px;
  line-height: 24px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #ffffff;
}
._section_testim .testim_vd {
  background: #ffffff url(../images/poster1.png) no-repeat right bottom;
  padding: 20px 30px;
  border-radius: 15px;
  height: 284px;
  position: relative;
  margin-top: 67px;
}
._section_testim .testim_vd h3 {
  font-size: 0;
  margin-bottom: 2px;
}
._section_testim .testim_vd h3 a {
  font-size: 32px;
  color: #0567FA;
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
}
._section_testim .testim_vd span {
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  font-style: italic;
  color: #777;
  margin-bottom: 25px;
  display: block;
}
._section_testim .testim_vd p {
  font-size: 14px;
  line-height: 24px;
  color: #303030;
font-family: 'Tajawal', sans-serif;  max-width: 60%;
}
._section_testim .testim_vd > a {
  font-weight: 700;
font-family: 'Tajawal', sans-serif;  color: #0567FA;
  font-size: 14px;
  position: absolute;
  left: 30px;
  bottom: 20px;
}
._section_testim .testim_vd > a:after {
  content: "\f3d6";
  font-family: "ionicons";
  margin: 10px;
  line-height: 0;
  position: relative;
  top: 4px;
  font-size: 22px;
}
._section_testim .testim_vd .btn_play {
  position: absolute;
  bottom: 0;
  right: 0;
  width: 103px;
  height: 75px;
  display: block;
  background: url(../images/plug2.png) no-repeat top left;
  text-align: center;
  line-height: 75px;
}
._section_testim .testim_vd .btn_play span {
  color: #ffffff;
  cursor: pointer;
  width: 0;
  height: 0;
  position: absolute;
  left: 50%;
  margin-left: -7px;
  font-size: 36px;
}
._section_testim .testim_vd .video-target {
  cursor: pointer;
}
._section_testim .testim_vd .video-wrapper {
  display: none;
  position: fixed;
  min-width: 100%;
  min-height: 100%;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: #000;
  z-index: 21000;
}
._section_testim .testim_vd .video-frame {
  position: absolute;
  top: 50%;
  left: 50%;
}
._section_testim .testim_vd .video-close {
  float: right;
  margin-top: -30px;
  margin-right: -30px;
  cursor: pointer;
  color: #fff;
  border: 1px solid #AEAEAE;
  border-radius: 30px;
  background: #605F61;
  font-size: 31px;
  font-weight: bold;
  display: inline-block;
  line-height: 0px;
  padding: 11px 3px;
}
._section_testim .testim_vd .video-close:before {
  content: "أ—";
}
._section_testim .box_location {
  text-align: center;
  border-radius: 30px;
  color: #ffffff;
  position: relative;
  overflow: hidden;
  background: url(../images/search.png) no-repeat top left;
}
._section_testim .box_location:after {
  content: "";
  left: 10px;
  top: 10px;
  right: 10px;
  bottom: 10px;
  background: rgba(104, 108, 16, 0.8);
  z-index: 0;
  position: absolute;
  border-radius: 15px;
}
._section_testim .box_location .ion-ios-location {
  font-size: 48px;
}
._section_testim .box_location .location_ {
  padding: 72px 56px;
  height: 516px;
  border-radius: 30px;
  overflow: hidden;
  border: 10px solid rgba(48, 87, 0, 0.7);
  position: relative;
  z-index: 2;
}
._section_testim .box_location .location_ li {
  line-height: 1;
}
._section_testim .box_location .location_ li .cter {
  font-size: 75px;
font-family: 'Tajawal', sans-serif;  font-weight: 900;
  line-height: 1;
  margin-top: 13px;
  margin-bottom: 10px;
  display: block;
}
._section_testim .box_location .location_ li p {
  display: block;
  line-height: 1;
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
}
._section_testim .box_location .location_ li hr {
  height: 2px;
  background: #ffffff;
  margin: 0;
  position: relative;
  top: 9px;
}
._section_testim .box_location .location_ li .ion-ios-heart {
  font-size: 18px;
}
._section_testim .box_location .location_ li p {
  line-height: 24px;
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  display: block;
}
._section_testim .box_location .location_ li a {
  width: 250px;
  height: 50px;
  border-radius: 50px;
  text-transform: uppercase;
  background: #f10027;
  color: #ffffff;
  line-height: 50px;
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  font-weight: 700;
  position: absolute;
  bottom: 72px;
  left: 50%;
  margin-left: -125px;
  display: block;
}
._section_testim .box_location .location_ li a:hover {
  -webkit-box-shadow: 0px 0px 15px 0px #e4e4e4;
  -moz-box-shadow: 0px 0px 15px 0px #e4e4e4;
  box-shadow: 0px 0px 15px 0px #e4e4e4;
}
._section_gallery {
  padding-top: 107px;
  padding-bottom: 140px;
}
._section_gallery .gallery_title {
  text-align: center;
  margin-bottom: 70px;
  color: #303030;
}
._section_gallery .gallery_title h3 {
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  font-size: 48px;
  margin-bottom: 13px;
}
._section_gallery .gallery_title h4 {
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  color: #0567FA;
  font-size: 36px;
  margin-bottom: 23px;
}
._section_gallery .gallery_title p {
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  line-height: 24px;
}
._section_gallery .gallery_nav {
  text-align: center;
  margin-bottom: 30px;
}
._section_gallery .gallery_nav button {
  border: 0;
  background: none;
  cursor: pointer;
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #777;
  text-transform: uppercase;
}
._section_gallery .gallery_nav button.is-checked {
  color: #0567FA;
}
._section_gallery .gallery_content .element-item {
  height: 250px;
  width: 31.624%;
  float: left;
  border-radius: 20px;
  margin-bottom: 30px;
}
._section_gallery .gallery_content .element-item .gallery_item {
  height: 100%;
  position: absolute;
  overflow: hidden;
}
._section_gallery .gallery_content .element-item .gallery_item img {
  border-radius: 20px;
  height: 100%;
  width: 100%;
}
._section_gallery .gallery_content .element-item .gallery_item:hover .child_hv {
  top: 30px;
  right: 30px;
  bottom: 30px;
  left: 30px;
  -webkit-transition-duration: .3s;
  -moz-transition-duration: .3s;
  transition-duration: .3s;
}
._section_gallery .gallery_content .element-item .gallery_item:hover .child_hv .ion-android-search {
  opacity: 1;
  transition-duration: 1.2s;
  -webkit-transition-duration: 1.2s;
  -moz-transition-duration: 1.2s;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv {
  position: absolute;
  top: -100%;
  left: 30px;
  right: 30px;
  bottom: 100%;
  padding-top: 34px;
  padding-bottom: 35px;
  background: rgba(42, 108, 61, 0.6);
  border-radius: 20px;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
  transition-duration: 0.3s;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv:before {
  content: "";
  position: absolute;
  left: 60px;
  top: -30px;
  width: 3px;
  height: 31px;
  background: url(../images/ten.png) no-repeat;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv:after {
  content: "";
  position: absolute;
  right: 60px;
  top: -30px;
  width: 3px;
  height: 31px;
  background: url(../images/ten.png) no-repeat;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv li {
  float: left;
  width: 100%;
  text-align: center;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv li:nth-of-type(1) {
  margin-bottom: 13px;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv li .ion-android-search {
  font-size: 48px;
  color: #ffffff;
  opacity: 0;
  line-height: 1;
  width: 0;
  height: 0;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv li .ion-android-search:before {
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv li .ion-android-search:hover:before {
  transform: rotate(90deg) scale(1.2);
  -webkit-transform: rotate(90deg) scale(1.2);
  -moz-transform: rotate(90deg) scale(1.2);
  transition-duration: 0.3s;
  -webkit-transition-duration: 0.3s;
  -moz-transition-duration: 0.3s;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv li .btn_cl {
  color: #ffffff;
font-family: 'Tajawal', sans-serif;  font-size: 24px;
  font-weight: 300;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv li .btn_cl:hover {
  text-shadow: 0 2px 2px #ffffff;
}
._section_gallery .gallery_content .element-item .gallery_item .child_hv li b {
  font-size: 12px;
font-family: 'Tajawal', sans-serif;  font-weight: 900;
  display: block;
  margin-top: 10px;
  color: #ffffff;
}
#imagelightbox {
  cursor: pointer;
  position: fixed;
  z-index: 10000;
  -ms-touch-action: none;
  touch-action: none;
  -webkit-box-shadow: 0 3px 20px 0 rgba(255, 255, 255, 0.5);
  /* 50 */
  box-shadow: 0 3px 20px 0 rgba(255, 255, 255, 0.5);
  /* 50 */
}
/* ACTIVITY INDICATION */
#imagelightbox-loading,
#imagelightbox-loading div {
  border-radius: 50%;
}
#imagelightbox-loading {
  width: 20px;
  /* 40 */
  height: 20px;
  /* 40 */
  background-color: #444;
  background-color: rgba(0, 0, 0, 0.5);
  position: fixed;
  z-index: 10003;
  text-align: center;
  top: 50%;
  left: 50%;
  padding: 0;
  /* 10 */
  margin: 0 auto;
  /* 20 */
  -webkit-box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  /* 40 */
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
  /* 40 */
}
#imagelightbox-loading div {
  width: 20px;
  /* 20 */
  height: 20px;
  /* 20 */
  background-color: #fff;
  -webkit-animation: imagelightbox-loading 0.5s ease infinite;
  animation: imagelightbox-loading 0.5s ease infinite;
}
@-webkit-keyframes imagelightbox-loading {
  from {
    opacity: .5;
    -webkit-transform: scale(0.75);
  }
  50% {
    opacity: 1;
    -webkit-transform: scale(1);
  }
  to {
    opacity: .5;
    -webkit-transform: scale(0.75);
  }
}
@keyframes imagelightbox-loading {
  from {
    opacity: .5;
    transform: scale(0.75);
  }
  50% {
    opacity: 1;
    transform: scale(1);
  }
  to {
    opacity: .5;
    transform: scale(0.75);
  }
}
/* OVERLAY */
#imagelightbox-overlay {
  background-color: #fff;
  background-color: rgba(0, 0, 0, 0.7);
  position: fixed;
  z-index: 9998;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}
.gutter-sizer {
  width: 2.565%;
}
._section_event {
  min-height: 633px;
  position: relative;
}
._section_event .box_parallax {
  position: absolute;
  height: 633px;
  overflow: hidden;
}
._section_event .box_parallax .parallax:before {
  content: "";
  background: rgba(60, 187, 134, 0.4);
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: 1;
}
._section_event .box_event {
  position: relative;
  z-index: 2;
}
._section_event .box_event .event_title {
  margin-top: 265px;
  color: #ffffff;
}
._section_event .box_event .event_title h3 {
  font-size: 48px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  margin-bottom: 13px;
  white-space: nowrap;
}
._section_event .box_event .event_title h4 {
  font-family: "Grand Hotel", cursive;
  font-weight: 400;
  white-space: nowrap;
  font-size: 36px;
  color: #0567FA;
  margin-bottom: 23px;
}
._section_event .box_event .event_title p {
  font-size: 14px;
  line-height: 24px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
}
._section_event .box_event .event_cs .event_item {
  height: 576px;
  border-radius: 15px;
  overflow: hidden;
}
._section_event .box_event .event_cs .event_item .box_img {
  position: relative;
  height: 355px;
  overflow: hidden;
}
._section_event .box_event .event_cs .event_item .box_img .shape {
  position: absolute;
  bottom: -41px;
  left: 0;
  height: 107px;
  width: 100%;
  background: url(../images/shape.png) no-repeat top center;
}
._section_event .box_event .event_cs .event_item .box_img img {
  float: left;
  height: 100%;
  border-radius: 15px 15px 0 0;
  transform: scale(1.2, 1);
}
._section_event .box_event .event_cs .event_item .event_content {
  background: #0567FA;
  padding: 30px;
  padding-top: 0;
  position: relative;
  height: 221px;
  border-radius: 0 0 15px 15px;
}
._section_event .box_event .event_cs .event_item .event_content h3 {
  font-size: 0;
  margin-bottom: 5px;
}
._section_event .box_event .event_cs .event_item .event_content h3 a {
  font-size: 30px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  color: #ffffff;
}
._section_event .box_event .event_cs .event_item .event_content dl {
  float: left;
  width: 100%;
  margin-bottom: 18px;
}
._section_event .box_event .event_cs .event_item .event_content dl dt {
  float: left;
  width: 50%;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #f9c0ab;
  font-size: 14px;
  font-style: italic;
}
._section_event .box_event .event_cs .event_item .event_content dl dt:before {
  margin-right: 5px;
  content: "\f3f3";
  font-family: "ionicons";
  line-height: 1;
}
._section_event .box_event .event_cs .event_item .event_content dl dd {
  float: left;
  width: 50%;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  color: #f9c0ab;
  font-size: 14px;
  font-style: italic;
}
._section_event .box_event .event_cs .event_item .event_content dl dd:before {
  margin-right: 5px;
  content: "\f3a0";
  font-family: "ionicons";
  line-height: 1;
}
._section_event .box_event .event_cs .event_item .event_content p {
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  line-height: 24px;
  color: #ffffff;
}
._section_event .box_event .event_cs .event_item .event_content > a {
  color: #ffffff;
  font-size: 14px;
font-family: 'Tajawal', sans-serif;  font-weight: 400;
  position: absolute;
  left: 30px;
  bottom: 40px;
}
._section_event .box_event .event_cs .event_item .event_content > a:after {
  content: "\f10b";
  font-family: "ionicons";
  margin-left: 5px;
  line-height: 1;
}
._section_question {
  min-height: 588px;
  padding-top: 159px;
  padding-bottom: 177px;
}
._section_question .q_title {
  text-align: center;
}
._section_question .q_title span {
  font-size: 72px;
  color: #0567FA;
}
._section_question .q_title h3 {
  font-size: 48px;
font-family: 'Tajawal', sans-serif;  font-weight: 300;
  margin-top: -5px;
  margin-bottom: 20px;
  color: #303030;
}
._section_question .q_title p {
  font-size: 14px;
  line-height: 24px;
font-family: 'Tajawal', sans-serif;  color: #303030;
  margin-bottom: 13px;
}
._section_question .q_title p a {
  font-weight: bold;
  text-decoration: underline;
  color: #303030;
}
._section_question .q_title p a:hover {
  text-decoration: none;
}
._section_question .q_title .qas {
  font-size: 16px;
font-family: 'Tajawal', sans-serif;  color: #0567FA;
  font-weight: 400;
}
._section_question .q_title .qas:after {
  content: "\f10b";
  font-family: "ionicons";
  margin-left: 11px;
  line-height: 1;
}
@-moz-document url-prefix() {
  .hpage_2 .ht_footer {
    overflow: hidden;
    padding-top: 80px;
  }
