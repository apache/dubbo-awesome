# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.636 ops/ms
# Warmup Iteration   2: 11.798 ops/ms
# Warmup Iteration   3: 12.135 ops/ms
Iteration   1: 12.264 ops/ms
Iteration   2: 12.409 ops/ms
Iteration   3: 12.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.396 ±(99.9%) 2.309 ops/ms [Average]
  (min, avg, max) = (12.264, 12.396, 12.516), stdev = 0.127
  CI (99.9%): [10.087, 14.705] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 8.167 ops/ms
# Warmup Iteration   2: 12.985 ops/ms
# Warmup Iteration   3: 12.941 ops/ms
Iteration   1: 12.798 ops/ms
Iteration   2: 12.896 ops/ms
Iteration   3: 12.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.825 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (12.780, 12.825, 12.896), stdev = 0.062
  CI (99.9%): [11.685, 13.964] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.680 ops/ms
# Warmup Iteration   2: 12.661 ops/ms
# Warmup Iteration   3: 12.837 ops/ms
Iteration   1: 12.767 ops/ms
Iteration   2: 12.779 ops/ms
Iteration   3: 12.750 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.765 ±(99.9%) 0.259 ops/ms [Average]
  (min, avg, max) = (12.750, 12.765, 12.779), stdev = 0.014
  CI (99.9%): [12.506, 13.025] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.566 ops/ms
# Warmup Iteration   2: 10.466 ops/ms
# Warmup Iteration   3: 10.332 ops/ms
Iteration   1: 10.514 ops/ms
Iteration   2: 10.455 ops/ms
Iteration   3: 10.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.487 ±(99.9%) 0.542 ops/ms [Average]
  (min, avg, max) = (10.455, 10.487, 10.514), stdev = 0.030
  CI (99.9%): [9.946, 11.029] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.199 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.540 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.003 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.511 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (2.494, 2.511, 2.540), stdev = 0.025
  CI (99.9%): [2.051, 2.970] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.784 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.003 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.483 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.488 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.483, 2.488, 2.495), stdev = 0.007
  CI (99.9%): [2.368, 2.607] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.288 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.004 ms/op
Iteration   3: 2.535 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.531 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.526, 2.531, 2.535), stdev = 0.005
  CI (99.9%): [2.445, 2.618] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.744 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.005 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
Iteration   2: 3.050 ±(99.9%) 0.007 ms/op
Iteration   3: 3.062 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.055 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (3.050, 3.055, 3.062), stdev = 0.006
  CI (99.9%): [2.940, 3.170] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.703 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
Iteration   1: 2.585 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.051 ms/op
                 createUser·p0.999:  12.277 ms/op
                 createUser·p0.9999: 14.470 ms/op
                 createUser·p1.00:   15.679 ms/op

Iteration   2: 2.595 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.067 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   4.092 ms/op
                 createUser·p0.999:  9.909 ms/op
                 createUser·p0.9999: 15.527 ms/op
                 createUser·p1.00:   16.630 ms/op

Iteration   3: 2.583 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.985 ms/op
                 createUser·p0.999:  8.753 ms/op
                 createUser·p0.9999: 11.123 ms/op
                 createUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 370646
  mean =      2.587 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 175991 
    [ 2.500,  3.750) = 188796 
    [ 3.750,  5.000) = 4470 
    [ 5.000,  6.250) = 798 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.142 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.041 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     15.153 ms/op
     p(99.9990) =     16.274 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.732 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  8.735 ms/op
                 existUser·p0.9999: 13.813 ms/op
                 existUser·p1.00:   13.959 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 14.242 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  9.478 ms/op
                 existUser·p0.9999: 11.783 ms/op
                 existUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384914
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 187675 
    [ 2.500,  3.750) = 192877 
    [ 3.750,  5.000) = 3207 
    [ 5.000,  6.250) = 568 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 129 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      9.471 ms/op
     p(99.9900) =     13.722 ms/op
     p(99.9990) =     15.027 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.963 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  11.613 ms/op
                 getUser·p0.9999: 14.041 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  10.553 ms/op
                 getUser·p0.9999: 15.195 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   3: 2.578 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.322 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  8.700 ms/op
                 getUser·p0.9999: 11.564 ms/op
                 getUser·p1.00:   13.140 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376489
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 181958 
    [ 2.500,  3.750) = 188021 
    [ 3.750,  5.000) = 4776 
    [ 5.000,  6.250) = 1123 
    [ 6.250,  7.500) = 153 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 124 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      8.757 ms/op
     p(99.9900) =     14.178 ms/op
     p(99.9990) =     15.802 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.709 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.009 ms/op
Iteration   1: 3.122 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   3.047 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   5.808 ms/op
                 listUser·p0.999:  8.733 ms/op
                 listUser·p0.9999: 10.548 ms/op
                 listUser·p1.00:   11.125 ms/op

Iteration   2: 3.108 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  10.355 ms/op
                 listUser·p0.9999: 12.337 ms/op
                 listUser·p1.00:   13.173 ms/op

Iteration   3: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.071 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  10.174 ms/op
                 listUser·p0.9999: 11.715 ms/op
                 listUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309153
  mean =      3.102 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 78259 
    [ 2.500,  3.750) = 183780 
    [ 3.750,  5.000) = 38146 
    [ 5.000,  6.250) = 7335 
    [ 6.250,  7.500) = 880 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 207 
    [10.000, 11.250) = 205 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.811 ms/op
     p(99.9900) =     11.928 ms/op
     p(99.9990) =     13.037 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.396 ± 2.309  ops/ms
ClientPb.existUser                       thrpt       3  12.825 ± 1.139  ops/ms
ClientPb.getUser                         thrpt       3  12.765 ± 0.259  ops/ms
ClientPb.listUser                        thrpt       3  10.487 ± 0.542  ops/ms
ClientPb.createUser                       avgt       3   2.511 ± 0.460   ms/op
ClientPb.existUser                        avgt       3   2.488 ± 0.120   ms/op
ClientPb.getUser                          avgt       3   2.531 ± 0.087   ms/op
ClientPb.listUser                         avgt       3   3.055 ± 0.115   ms/op
ClientPb.createUser                     sample  370646   2.587 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.715           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.041           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.962           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.153           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.630           ms/op
ClientPb.existUser                      sample  384914   2.491 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.884           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.471           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.722           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.057           ms/op
ClientPb.getUser                        sample  376489   2.547 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.580           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.757           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.178           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.876           ms/op
ClientPb.listUser                       sample  309153   3.102 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.826           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.811           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.928           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.173           ms/op
