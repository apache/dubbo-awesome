# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.735 ops/ms
# Warmup Iteration   2: 3.624 ops/ms
# Warmup Iteration   3: 7.323 ops/ms
Iteration   1: 7.791 ops/ms
Iteration   2: 8.235 ops/ms
Iteration   3: 8.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.058 ±(99.9%) 4.294 ops/ms [Average]
  (min, avg, max) = (7.791, 8.058, 8.235), stdev = 0.235
  CI (99.9%): [3.764, 12.352] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.326 ops/ms
# Warmup Iteration   2: 7.116 ops/ms
# Warmup Iteration   3: 7.926 ops/ms
Iteration   1: 8.494 ops/ms
Iteration   2: 8.648 ops/ms
Iteration   3: 8.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.527 ±(99.9%) 1.966 ops/ms [Average]
  (min, avg, max) = (8.440, 8.527, 8.648), stdev = 0.108
  CI (99.9%): [6.561, 10.494] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.177 ops/ms
# Warmup Iteration   2: 6.702 ops/ms
# Warmup Iteration   3: 7.959 ops/ms
Iteration   1: 8.073 ops/ms
Iteration   2: 8.119 ops/ms
Iteration   3: 8.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.190 ±(99.9%) 3.011 ops/ms [Average]
  (min, avg, max) = (8.073, 8.190, 8.379), stdev = 0.165
  CI (99.9%): [5.179, 11.202] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.114 ops/ms
# Warmup Iteration   2: 5.676 ops/ms
# Warmup Iteration   3: 6.543 ops/ms
Iteration   1: 6.885 ops/ms
Iteration   2: 6.501 ops/ms
Iteration   3: 6.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.784 ±(99.9%) 4.538 ops/ms [Average]
  (min, avg, max) = (6.501, 6.784, 6.966), stdev = 0.249
  CI (99.9%): [2.246, 11.322] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.145 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.662 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.005 ms/op
Iteration   1: 3.915 ±(99.9%) 0.006 ms/op
Iteration   2: 4.075 ±(99.9%) 0.005 ms/op
Iteration   3: 3.857 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.949 ±(99.9%) 2.051 ms/op [Average]
  (min, avg, max) = (3.857, 3.949, 4.075), stdev = 0.112
  CI (99.9%): [1.898, 6.001] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.945 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.199 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.770 ±(99.9%) 0.012 ms/op
Iteration   1: 3.781 ±(99.9%) 0.008 ms/op
Iteration   2: 3.812 ±(99.9%) 0.004 ms/op
Iteration   3: 3.663 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.752 ±(99.9%) 1.440 ms/op [Average]
  (min, avg, max) = (3.663, 3.752, 3.812), stdev = 0.079
  CI (99.9%): [2.312, 5.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.097 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.004 ms/op
Iteration   1: 4.041 ±(99.9%) 0.010 ms/op
Iteration   2: 4.078 ±(99.9%) 0.013 ms/op
Iteration   3: 4.097 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.072 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (4.041, 4.072, 4.097), stdev = 0.029
  CI (99.9%): [3.551, 4.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.442 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.797 ±(99.9%) 0.006 ms/op
Iteration   1: 4.702 ±(99.9%) 0.007 ms/op
Iteration   2: 4.375 ±(99.9%) 0.016 ms/op
Iteration   3: 4.465 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.514 ±(99.9%) 3.086 ms/op [Average]
  (min, avg, max) = (4.375, 4.514, 4.702), stdev = 0.169
  CI (99.9%): [1.428, 7.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.727 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.991 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.402 ±(99.9%) 0.018 ms/op
Iteration   1: 3.782 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  22.787 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   2: 3.905 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.760 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  25.690 ms/op
                 createUser·p0.9999: 31.123 ms/op
                 createUser·p1.00:   31.949 ms/op

Iteration   3: 3.850 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.927 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.574 ms/op
                 createUser·p0.999:  14.744 ms/op
                 createUser·p0.9999: 32.178 ms/op
                 createUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 249595
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 429 
    [ 2.500,  5.000) = 241764 
    [ 5.000,  7.500) = 5630 
    [ 7.500, 10.000) = 1211 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     22.623 ms/op
     p(99.9900) =     30.639 ms/op
     p(99.9990) =     33.015 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.934 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.012 ms/op
Iteration   1: 3.824 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.794 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.674 ms/op
                 existUser·p0.99:   6.469 ms/op
                 existUser·p0.999:  26.915 ms/op
                 existUser·p0.9999: 38.642 ms/op
                 existUser·p1.00:   40.305 ms/op

Iteration   2: 3.788 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   7.356 ms/op
                 existUser·p0.999:  13.617 ms/op
                 existUser·p0.9999: 26.509 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   3: 3.785 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.917 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  27.132 ms/op
                 existUser·p0.9999: 38.535 ms/op
                 existUser·p1.00:   39.125 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 252556
  mean =      3.799 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 244089 
    [ 5.000, 10.000) = 7925 
    [10.000, 15.000) = 283 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 161 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 60 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     23.556 ms/op
     p(99.9900) =     38.142 ms/op
     p(99.9990) =     39.318 ms/op
     p(99.9999) =     40.305 ms/op
    p(100.0000) =     40.305 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.338 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 4.662 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.131 ±(99.9%) 0.012 ms/op
Iteration   1: 3.996 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.927 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 25.788 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 3.981 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.616 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.912 ms/op
                 getUser·p0.999:  14.850 ms/op
                 getUser·p0.9999: 26.738 ms/op
                 getUser·p1.00:   27.951 ms/op

Iteration   3: 3.939 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.447 ms/op
                 getUser·p0.999:  25.100 ms/op
                 getUser·p0.9999: 29.152 ms/op
                 getUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 241491
  mean =      3.972 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 231173 
    [ 5.000,  7.500) = 8195 
    [ 7.500, 10.000) = 1222 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     28.503 ms/op
     p(99.9990) =     29.942 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.612 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 6.002 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.938 ±(99.9%) 0.018 ms/op
Iteration   1: 4.716 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   9.014 ms/op
                 listUser·p0.999:  25.861 ms/op
                 listUser·p0.9999: 30.219 ms/op
                 listUser·p1.00:   31.425 ms/op

Iteration   2: 4.705 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.638 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.822 ms/op
                 listUser·p0.999:  18.711 ms/op
                 listUser·p0.9999: 27.794 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   3: 4.629 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.753 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   8.515 ms/op
                 listUser·p0.999:  15.565 ms/op
                 listUser·p0.9999: 17.733 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204859
  mean =      4.683 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 174595 
    [ 5.000,  7.500) = 25898 
    [ 7.500, 10.000) = 3180 
    [10.000, 12.500) = 609 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.845 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      8.716 ms/op
     p(99.9000) =     18.519 ms/op
     p(99.9900) =     28.591 ms/op
     p(99.9990) =     31.186 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.058 ± 4.294  ops/ms
ClientPb.existUser                       thrpt       3   8.527 ± 1.966  ops/ms
ClientPb.getUser                         thrpt       3   8.190 ± 3.011  ops/ms
ClientPb.listUser                        thrpt       3   6.784 ± 4.538  ops/ms
ClientPb.createUser                       avgt       3   3.949 ± 2.051   ms/op
ClientPb.existUser                        avgt       3   3.752 ± 1.440   ms/op
ClientPb.getUser                          avgt       3   4.072 ± 0.521   ms/op
ClientPb.listUser                         avgt       3   4.514 ± 3.086   ms/op
ClientPb.createUser                     sample  249595   3.845 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.456           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.588           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.623           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.639           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.996           ms/op
ClientPb.existUser                      sample  252556   3.799 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.417           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.661           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.865           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.556           ms/op
ClientPb.existUser:existUser·p0.9999    sample          38.142           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.305           ms/op
ClientPb.getUser                        sample  241491   3.972 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.616           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.858           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.266           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.503           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.015           ms/op
ClientPb.listUser                       sample  204859   4.683 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.845           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.136           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.716           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.591           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.425           ms/op
