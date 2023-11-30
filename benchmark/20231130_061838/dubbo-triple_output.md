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
# Warmup Iteration   1: 5.212 ops/ms
# Warmup Iteration   2: 11.997 ops/ms
# Warmup Iteration   3: 12.447 ops/ms
Iteration   1: 12.713 ops/ms
Iteration   2: 12.855 ops/ms
Iteration   3: 12.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.775 ±(99.9%) 1.320 ops/ms [Average]
  (min, avg, max) = (12.713, 12.775, 12.855), stdev = 0.072
  CI (99.9%): [11.455, 14.095] (assumes normal distribution)


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
# Warmup Iteration   1: 8.499 ops/ms
# Warmup Iteration   2: 13.073 ops/ms
# Warmup Iteration   3: 13.006 ops/ms
Iteration   1: 13.031 ops/ms
Iteration   2: 13.128 ops/ms
Iteration   3: 13.021 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.060 ±(99.9%) 1.083 ops/ms [Average]
  (min, avg, max) = (13.021, 13.060, 13.128), stdev = 0.059
  CI (99.9%): [11.977, 14.143] (assumes normal distribution)


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
# Warmup Iteration   1: 7.886 ops/ms
# Warmup Iteration   2: 12.725 ops/ms
# Warmup Iteration   3: 12.828 ops/ms
Iteration   1: 12.894 ops/ms
Iteration   2: 12.812 ops/ms
Iteration   3: 12.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.818 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (12.748, 12.818, 12.894), stdev = 0.073
  CI (99.9%): [11.491, 14.145] (assumes normal distribution)


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
# Warmup Iteration   1: 6.614 ops/ms
# Warmup Iteration   2: 10.287 ops/ms
# Warmup Iteration   3: 10.635 ops/ms
Iteration   1: 10.529 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.575 ±(99.9%) 0.838 ops/ms [Average]
  (min, avg, max) = (10.529, 10.575, 10.621), stdev = 0.046
  CI (99.9%): [9.736, 11.413] (assumes normal distribution)


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.521 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.531 ±(99.9%) 0.168 ms/op [Average]
  (min, avg, max) = (2.521, 2.531, 2.538), stdev = 0.009
  CI (99.9%): [2.364, 2.699] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.805 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
Iteration   2: 2.442 ±(99.9%) 0.003 ms/op
Iteration   3: 2.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.449 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (2.442, 2.449, 2.459), stdev = 0.009
  CI (99.9%): [2.290, 2.608] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.004 ms/op
Iteration   2: 2.481 ±(99.9%) 0.003 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.478 ±(99.9%) 0.051 ms/op [Average]
  (min, avg, max) = (2.476, 2.478, 2.481), stdev = 0.003
  CI (99.9%): [2.427, 2.529] (assumes normal distribution)


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
Iteration   3: 3.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.041 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (3.033, 3.041, 3.053), stdev = 0.011
  CI (99.9%): [2.848, 3.234] (assumes normal distribution)


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.675 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.727 ms/op
                 createUser·p0.999:  11.289 ms/op
                 createUser·p0.9999: 14.203 ms/op
                 createUser·p1.00:   14.811 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.482 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 12.456 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   3: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  8.251 ms/op
                 createUser·p0.9999: 11.869 ms/op
                 createUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380292
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 180892 
    [ 2.500,  3.750) = 195962 
    [ 3.750,  5.000) = 2624 
    [ 5.000,  6.250) = 324 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.626 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      8.266 ms/op
     p(99.9900) =     13.188 ms/op
     p(99.9990) =     14.762 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 3.726 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
Iteration   1: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  5.063 ms/op
                 existUser·p0.9999: 13.579 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.639 ms/op
                 existUser·p0.999:  6.759 ms/op
                 existUser·p0.9999: 12.141 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   4.027 ms/op
                 existUser·p0.999:  7.109 ms/op
                 existUser·p0.9999: 11.863 ms/op
                 existUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390305
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 194704 
    [ 2.500,  3.750) = 191809 
    [ 3.750,  5.000) = 2816 
    [ 5.000,  6.250) = 567 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      5.929 ms/op
     p(99.9900) =     13.036 ms/op
     p(99.9990) =     13.980 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 3.969 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  8.878 ms/op
                 getUser·p0.9999: 14.955 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  10.151 ms/op
                 getUser·p0.9999: 14.308 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.080 ms/op
                 getUser·p0.999:  7.722 ms/op
                 getUser·p0.9999: 10.486 ms/op
                 getUser·p1.00:   10.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383104
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 188951 
    [ 2.500,  3.750) = 189326 
    [ 3.750,  5.000) = 3683 
    [ 5.000,  6.250) = 632 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.887 ms/op
     p(99.9000) =      7.744 ms/op
     p(99.9900) =     14.418 ms/op
     p(99.9990) =     15.248 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 4.877 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.009 ms/op
Iteration   1: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.849 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  8.718 ms/op
                 listUser·p0.9999: 10.273 ms/op
                 listUser·p1.00:   10.437 ms/op

Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.774 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 11.744 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   3: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.865 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.106 ms/op
                 listUser·p0.9999: 14.010 ms/op
                 listUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320150
  mean =      2.996 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 169 
    [ 1.250,  2.500) = 95631 
    [ 2.500,  3.750) = 185087 
    [ 3.750,  5.000) = 31791 
    [ 5.000,  6.250) = 6081 
    [ 6.250,  7.500) = 734 
    [ 7.500,  8.750) = 289 
    [ 8.750, 10.000) = 207 
    [10.000, 11.250) = 113 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     12.865 ms/op
     p(99.9990) =     14.195 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.775 ± 1.320  ops/ms
ClientPb.existUser                       thrpt       3  13.060 ± 1.083  ops/ms
ClientPb.getUser                         thrpt       3  12.818 ± 1.327  ops/ms
ClientPb.listUser                        thrpt       3  10.575 ± 0.838  ops/ms
ClientPb.createUser                       avgt       3   2.531 ± 0.168   ms/op
ClientPb.existUser                        avgt       3   2.449 ± 0.159   ms/op
ClientPb.getUser                          avgt       3   2.478 ± 0.051   ms/op
ClientPb.listUser                         avgt       3   3.041 ± 0.193   ms/op
ClientPb.createUser                     sample  380292   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.626           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.266           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.188           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.811           ms/op
ClientPb.existUser                      sample  390305   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.929           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.036           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.189           ms/op
ClientPb.getUser                        sample  383104   2.504 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.812           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.744           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.418           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.614           ms/op
ClientPb.listUser                       sample  320150   2.996 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.774           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.060           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.865           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.942           ms/op
