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
# Warmup Iteration   1: 4.386 ops/ms
# Warmup Iteration   2: 11.763 ops/ms
# Warmup Iteration   3: 12.107 ops/ms
Iteration   1: 12.340 ops/ms
Iteration   2: 12.250 ops/ms
Iteration   3: 12.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.350 ±(99.9%) 1.919 ops/ms [Average]
  (min, avg, max) = (12.250, 12.350, 12.459), stdev = 0.105
  CI (99.9%): [10.431, 14.269] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.829 ops/ms
# Warmup Iteration   2: 12.862 ops/ms
# Warmup Iteration   3: 12.871 ops/ms
Iteration   1: 12.892 ops/ms
Iteration   2: 12.812 ops/ms
Iteration   3: 12.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.870 ±(99.9%) 0.906 ops/ms [Average]
  (min, avg, max) = (12.812, 12.870, 12.904), stdev = 0.050
  CI (99.9%): [11.963, 13.776] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.659 ops/ms
# Warmup Iteration   2: 12.156 ops/ms
# Warmup Iteration   3: 12.560 ops/ms
Iteration   1: 12.640 ops/ms
Iteration   2: 12.503 ops/ms
Iteration   3: 12.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.594 ±(99.9%) 1.432 ops/ms [Average]
  (min, avg, max) = (12.503, 12.594, 12.640), stdev = 0.079
  CI (99.9%): [11.162, 14.026] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.425 ops/ms
# Warmup Iteration   2: 10.403 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.449 ops/ms
Iteration   2: 10.373 ops/ms
Iteration   3: 10.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.389 ±(99.9%) 0.979 ops/ms [Average]
  (min, avg, max) = (10.345, 10.389, 10.449), stdev = 0.054
  CI (99.9%): [9.410, 11.369] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.232 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.576 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.544 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (2.520, 2.544, 2.576), stdev = 0.029
  CI (99.9%): [2.017, 3.071] (assumes normal distribution)


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.502 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.500 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (2.494, 2.500, 2.503), stdev = 0.005
  CI (99.9%): [2.402, 2.598] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.987 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.004 ms/op
Iteration   1: 2.544 ±(99.9%) 0.005 ms/op
Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
Iteration   3: 2.531 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.530 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.515, 2.530, 2.544), stdev = 0.014
  CI (99.9%): [2.270, 2.789] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.100 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
Iteration   1: 3.041 ±(99.9%) 0.007 ms/op
Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
Iteration   3: 3.039 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.038 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (3.033, 3.038, 3.041), stdev = 0.004
  CI (99.9%): [2.957, 3.118] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.269 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.701 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.580 ±(99.9%) 0.006 ms/op
Iteration   1: 2.575 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.269 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  12.819 ms/op
                 createUser·p0.9999: 20.925 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  10.774 ms/op
                 createUser·p0.9999: 13.131 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   3: 2.565 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  7.951 ms/op
                 createUser·p0.9999: 11.354 ms/op
                 createUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374129
  mean =      2.565 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 178172 
    [ 2.500,  5.000) = 194720 
    [ 5.000,  7.500) = 799 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      9.126 ms/op
     p(99.9900) =     17.733 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.787 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  7.611 ms/op
                 existUser·p0.9999: 20.643 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  5.523 ms/op
                 existUser·p0.9999: 13.403 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   4.035 ms/op
                 existUser·p0.999:  8.229 ms/op
                 existUser·p0.9999: 11.013 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388527
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191167 
    [ 2.500,  5.000) = 196464 
    [ 5.000,  7.500) = 530 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      6.791 ms/op
     p(99.9900) =     14.575 ms/op
     p(99.9990) =     21.500 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.588 ±(99.9%) 0.006 ms/op
Iteration   1: 2.558 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  12.468 ms/op
                 getUser·p0.9999: 14.787 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   2: 2.581 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.138 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  9.865 ms/op
                 getUser·p0.9999: 18.534 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   3: 2.561 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 12.124 ms/op
                 getUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373748
  mean =      2.566 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 181570 
    [ 2.500,  3.750) = 187130 
    [ 3.750,  5.000) = 3956 
    [ 5.000,  6.250) = 627 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.121 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      8.819 ms/op
     p(99.9900) =     14.903 ms/op
     p(99.9990) =     18.769 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 4.917 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.009 ms/op
Iteration   1: 3.104 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.035 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 14.195 ms/op
                 listUser·p1.00:   14.565 ms/op

Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   3.056 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.865 ms/op
                 listUser·p0.999:  9.726 ms/op
                 listUser·p0.9999: 11.612 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   3: 3.097 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  10.298 ms/op
                 listUser·p0.9999: 11.480 ms/op
                 listUser·p1.00:   12.337 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 308607
  mean =      3.108 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 73510 
    [ 2.500,  3.750) = 189501 
    [ 3.750,  5.000) = 37206 
    [ 5.000,  6.250) = 6747 
    [ 6.250,  7.500) = 847 
    [ 7.500,  8.750) = 130 
    [ 8.750, 10.000) = 284 
    [10.000, 11.250) = 207 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =      9.870 ms/op
     p(99.9900) =     12.241 ms/op
     p(99.9990) =     14.482 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.350 ± 1.919  ops/ms
ClientPb.existUser                       thrpt       3  12.870 ± 0.906  ops/ms
ClientPb.getUser                         thrpt       3  12.594 ± 1.432  ops/ms
ClientPb.listUser                        thrpt       3  10.389 ± 0.979  ops/ms
ClientPb.createUser                       avgt       3   2.544 ± 0.527   ms/op
ClientPb.existUser                        avgt       3   2.500 ± 0.098   ms/op
ClientPb.getUser                          avgt       3   2.530 ± 0.259   ms/op
ClientPb.listUser                         avgt       3   3.038 ± 0.081   ms/op
ClientPb.createUser                     sample  374129   2.565 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.876           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.126           ms/op
ClientPb.createUser:createUser·p0.9999  sample          17.733           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.135           ms/op
ClientPb.existUser                      sample  388527   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.787           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.791           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.575           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.692           ms/op
ClientPb.getUser                        sample  373748   2.566 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.869           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.589           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.819           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.903           ms/op
ClientPb.getUser:getUser·p1.00          sample          19.071           ms/op
ClientPb.listUser                       sample  308607   3.108 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.798           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.043           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.734           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.870           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.241           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.565           ms/op
