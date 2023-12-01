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
# Warmup Iteration   1: 4.878 ops/ms
# Warmup Iteration   2: 12.042 ops/ms
# Warmup Iteration   3: 12.412 ops/ms
Iteration   1: 12.510 ops/ms
Iteration   2: 12.759 ops/ms
Iteration   3: 12.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.658 ±(99.9%) 2.392 ops/ms [Average]
  (min, avg, max) = (12.510, 12.658, 12.759), stdev = 0.131
  CI (99.9%): [10.266, 15.051] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.455 ops/ms
# Warmup Iteration   2: 12.865 ops/ms
# Warmup Iteration   3: 12.954 ops/ms
Iteration   1: 12.799 ops/ms
Iteration   2: 13.036 ops/ms
Iteration   3: 12.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.927 ±(99.9%) 2.181 ops/ms [Average]
  (min, avg, max) = (12.799, 12.927, 13.036), stdev = 0.120
  CI (99.9%): [10.746, 15.108] (assumes normal distribution)


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
# Warmup Iteration   1: 8.098 ops/ms
# Warmup Iteration   2: 12.393 ops/ms
# Warmup Iteration   3: 12.709 ops/ms
Iteration   1: 12.615 ops/ms
Iteration   2: 12.811 ops/ms
Iteration   3: 12.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.727 ±(99.9%) 1.843 ops/ms [Average]
  (min, avg, max) = (12.615, 12.727, 12.811), stdev = 0.101
  CI (99.9%): [10.884, 14.571] (assumes normal distribution)


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
# Warmup Iteration   1: 6.820 ops/ms
# Warmup Iteration   2: 10.491 ops/ms
# Warmup Iteration   3: 10.406 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.716 ops/ms
Iteration   3: 10.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.648 ±(99.9%) 1.188 ops/ms [Average]
  (min, avg, max) = (10.586, 10.648, 10.716), stdev = 0.065
  CI (99.9%): [9.460, 11.836] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.120 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.005 ms/op
Iteration   1: 2.590 ±(99.9%) 0.003 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.517 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.686 ms/op [Average]
  (min, avg, max) = (2.517, 2.549, 2.590), stdev = 0.038
  CI (99.9%): [1.864, 3.235] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.669 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.003 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.488 ±(99.9%) 0.278 ms/op [Average]
  (min, avg, max) = (2.473, 2.488, 2.503), stdev = 0.015
  CI (99.9%): [2.210, 2.766] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.489 ±(99.9%) 0.034 ms/op [Average]
  (min, avg, max) = (2.487, 2.489, 2.490), stdev = 0.002
  CI (99.9%): [2.455, 2.523] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.792 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.005 ms/op
Iteration   1: 3.055 ±(99.9%) 0.004 ms/op
Iteration   2: 3.045 ±(99.9%) 0.006 ms/op
Iteration   3: 3.040 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.047 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (3.040, 3.047, 3.055), stdev = 0.008
  CI (99.9%): [2.909, 3.185] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.307 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.691 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.006 ms/op
Iteration   1: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  11.542 ms/op
                 createUser·p0.9999: 15.943 ms/op
                 createUser·p1.00:   16.843 ms/op

Iteration   2: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.027 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 11.895 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   3: 2.570 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.865 ms/op
                 createUser·p0.999:  9.120 ms/op
                 createUser·p0.9999: 12.911 ms/op
                 createUser·p1.00:   13.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374352
  mean =      2.562 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 178108 
    [ 2.500,  3.750) = 191363 
    [ 3.750,  5.000) = 3775 
    [ 5.000,  6.250) = 585 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 116 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      9.120 ms/op
     p(99.9900) =     14.144 ms/op
     p(99.9990) =     16.601 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.662 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.466 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.110 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  6.581 ms/op
                 existUser·p0.9999: 14.139 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  5.972 ms/op
                 existUser·p0.9999: 13.103 ms/op
                 existUser·p1.00:   14.172 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.973 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  7.725 ms/op
                 existUser·p0.9999: 11.636 ms/op
                 existUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388824
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 192024 
    [ 2.500,  3.750) = 193012 
    [ 3.750,  5.000) = 2924 
    [ 5.000,  6.250) = 370 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      7.221 ms/op
     p(99.9900) =     13.404 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  10.748 ms/op
                 getUser·p0.9999: 13.753 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  9.387 ms/op
                 getUser·p0.9999: 12.796 ms/op
                 getUser·p1.00:   13.582 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  7.902 ms/op
                 getUser·p0.9999: 11.636 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380026
  mean =      2.524 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 187092 
    [ 2.500,  3.750) = 188237 
    [ 3.750,  5.000) = 3649 
    [ 5.000,  6.250) = 564 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     13.930 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.964 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.009 ms/op
Iteration   1: 3.081 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.758 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.975 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.707 ms/op
                 listUser·p0.9999: 10.379 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   2: 3.115 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.064 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.833 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.415 ms/op
                 listUser·p1.00:   13.582 ms/op

Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.664 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 11.932 ms/op
                 listUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310186
  mean =      3.092 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 78965 
    [ 2.500,  3.750) = 186562 
    [ 3.750,  5.000) = 36179 
    [ 5.000,  6.250) = 6859 
    [ 6.250,  7.500) = 859 
    [ 7.500,  8.750) = 280 
    [ 8.750, 10.000) = 266 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      9.057 ms/op
     p(99.9900) =     11.288 ms/op
     p(99.9990) =     13.364 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.658 ± 2.392  ops/ms
ClientPb.existUser                       thrpt       3  12.927 ± 2.181  ops/ms
ClientPb.getUser                         thrpt       3  12.727 ± 1.843  ops/ms
ClientPb.listUser                        thrpt       3  10.648 ± 1.188  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.686   ms/op
ClientPb.existUser                        avgt       3   2.488 ± 0.278   ms/op
ClientPb.getUser                          avgt       3   2.489 ± 0.034   ms/op
ClientPb.listUser                         avgt       3   3.047 ± 0.138   ms/op
ClientPb.createUser                     sample  374352   2.562 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.668           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.120           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.144           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.843           ms/op
ClientPb.existUser                      sample  388824   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.873           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.221           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.404           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.631           ms/op
ClientPb.getUser                        sample  380026   2.524 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.714           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.503           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.287           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.025           ms/op
ClientPb.listUser                       sample  310186   3.092 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.664           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.035           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.057           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.288           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.582           ms/op
