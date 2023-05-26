# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.635 ops/ms
# Warmup Iteration   2: 6.614 ops/ms
# Warmup Iteration   3: 9.502 ops/ms
Iteration   1: 9.909 ops/ms
Iteration   2: 9.901 ops/ms
Iteration   3: 9.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.897 ±(99.9%) 0.273 ops/ms [Average]
  (min, avg, max) = (9.880, 9.897, 9.909), stdev = 0.015
  CI (99.9%): [9.624, 10.170] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.237 ops/ms
# Warmup Iteration   2: 9.458 ops/ms
# Warmup Iteration   3: 9.646 ops/ms
Iteration   1: 9.861 ops/ms
Iteration   2: 9.962 ops/ms
Iteration   3: 10.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.170 ±(99.9%) 8.204 ops/ms [Average]
  (min, avg, max) = (9.861, 10.170, 10.686), stdev = 0.450
  CI (99.9%): [1.966, 18.373] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.455 ops/ms
# Warmup Iteration   2: 9.305 ops/ms
# Warmup Iteration   3: 9.868 ops/ms
Iteration   1: 10.004 ops/ms
Iteration   2: 10.183 ops/ms
Iteration   3: 9.914 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.034 ±(99.9%) 2.501 ops/ms [Average]
  (min, avg, max) = (9.914, 10.034, 10.183), stdev = 0.137
  CI (99.9%): [7.533, 12.534] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.215 ops/ms
# Warmup Iteration   2: 7.774 ops/ms
# Warmup Iteration   3: 8.095 ops/ms
Iteration   1: 8.565 ops/ms
Iteration   2: 8.326 ops/ms
Iteration   3: 8.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.446 ±(99.9%) 2.180 ops/ms [Average]
  (min, avg, max) = (8.326, 8.446, 8.565), stdev = 0.119
  CI (99.9%): [6.267, 10.626] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.644 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.389 ±(99.9%) 0.003 ms/op
Iteration   1: 3.184 ±(99.9%) 0.006 ms/op
Iteration   2: 3.160 ±(99.9%) 0.009 ms/op
Iteration   3: 3.235 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.193 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (3.160, 3.193, 3.235), stdev = 0.038
  CI (99.9%): [2.495, 3.890] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.365 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.279 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.006 ms/op
Iteration   1: 3.309 ±(99.9%) 0.005 ms/op
Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
Iteration   3: 3.159 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.177 ±(99.9%) 2.276 ms/op [Average]
  (min, avg, max) = (3.062, 3.177, 3.309), stdev = 0.125
  CI (99.9%): [0.900, 5.453] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.228 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.002 ms/op
Iteration   1: 3.224 ±(99.9%) 0.007 ms/op
Iteration   2: 3.239 ±(99.9%) 0.007 ms/op
Iteration   3: 3.114 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.192 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (3.114, 3.192, 3.239), stdev = 0.068
  CI (99.9%): [1.952, 4.433] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.078 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.009 ms/op
Iteration   1: 3.802 ±(99.9%) 0.003 ms/op
Iteration   2: 3.727 ±(99.9%) 0.005 ms/op
Iteration   3: 3.787 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.772 ±(99.9%) 0.724 ms/op [Average]
  (min, avg, max) = (3.727, 3.772, 3.802), stdev = 0.040
  CI (99.9%): [3.048, 4.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.712 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.670 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.008 ms/op
Iteration   1: 3.218 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 22.610 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 3.222 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  11.153 ms/op
                 createUser·p0.9999: 30.507 ms/op
                 createUser·p1.00:   31.392 ms/op

Iteration   3: 3.262 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.571 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  15.676 ms/op
                 createUser·p0.9999: 30.939 ms/op
                 createUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296584
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19096 
    [ 2.500,  5.000) = 271496 
    [ 5.000,  7.500) = 4931 
    [ 7.500, 10.000) = 535 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     16.486 ms/op
     p(99.9900) =     30.420 ms/op
     p(99.9990) =     32.285 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.850 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  10.306 ms/op
                 existUser·p0.9999: 22.397 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.593 ms/op
                 existUser·p0.999:  13.500 ms/op
                 existUser·p0.9999: 24.727 ms/op
                 existUser·p1.00:   25.625 ms/op

Iteration   3: 3.336 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  14.923 ms/op
                 existUser·p0.9999: 22.872 ms/op
                 existUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302845
  mean =      3.167 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12961 
    [ 2.500,  5.000) = 282936 
    [ 5.000,  7.500) = 6113 
    [ 7.500, 10.000) = 471 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     13.159 ms/op
     p(99.9900) =     23.237 ms/op
     p(99.9990) =     25.361 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.253 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.009 ms/op
Iteration   1: 3.171 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   5.728 ms/op
                 getUser·p0.999:  16.648 ms/op
                 getUser·p0.9999: 19.169 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   2: 3.248 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   4.187 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  19.562 ms/op
                 getUser·p0.9999: 22.886 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.706 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  15.306 ms/op
                 getUser·p0.9999: 23.348 ms/op
                 getUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295611
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11463 
    [ 2.500,  5.000) = 277766 
    [ 5.000,  7.500) = 5236 
    [ 7.500, 10.000) = 619 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     17.052 ms/op
     p(99.9900) =     22.872 ms/op
     p(99.9990) =     24.119 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.501 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.374 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.014 ms/op
Iteration   1: 3.844 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.948 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 21.485 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 3.666 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.084 ms/op
                 listUser·p0.99:   6.587 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 14.733 ms/op
                 listUser·p1.00:   15.041 ms/op

Iteration   3: 3.789 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  12.714 ms/op
                 listUser·p0.9999: 15.647 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254902
  mean =      3.765 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 246360 
    [ 5.000,  7.500) = 6555 
    [ 7.500, 10.000) = 1223 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 281 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     20.481 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.897 ± 0.273  ops/ms
ClientPb.existUser                       thrpt       3  10.170 ± 8.204  ops/ms
ClientPb.getUser                         thrpt       3  10.034 ± 2.501  ops/ms
ClientPb.listUser                        thrpt       3   8.446 ± 2.180  ops/ms
ClientPb.createUser                       avgt       3   3.193 ± 0.698   ms/op
ClientPb.existUser                        avgt       3   3.177 ± 2.276   ms/op
ClientPb.getUser                          avgt       3   3.192 ± 1.241   ms/op
ClientPb.listUser                         avgt       3   3.772 ± 0.724   ms/op
ClientPb.createUser                     sample  296584   3.234 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.118           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.564           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.486           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.420           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.571           ms/op
ClientPb.existUser                      sample  302845   3.167 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.851           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.159           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.237           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.625           ms/op
ClientPb.getUser                        sample  295611   3.246 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.036           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.784           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.052           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.872           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.314           ms/op
ClientPb.listUser                       sample  254902   3.765 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.651           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.662           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.779           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.481           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.151           ms/op
