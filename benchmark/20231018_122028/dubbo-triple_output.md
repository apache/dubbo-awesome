# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.698 ops/ms
# Warmup Iteration   2: 4.021 ops/ms
# Warmup Iteration   3: 7.378 ops/ms
Iteration   1: 7.659 ops/ms
Iteration   2: 7.895 ops/ms
Iteration   3: 7.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.818 ±(99.9%) 2.521 ops/ms [Average]
  (min, avg, max) = (7.659, 7.818, 7.901), stdev = 0.138
  CI (99.9%): [5.297, 10.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.450 ops/ms
# Warmup Iteration   2: 6.276 ops/ms
# Warmup Iteration   3: 7.841 ops/ms
Iteration   1: 7.819 ops/ms
Iteration   2: 8.209 ops/ms
Iteration   3: 8.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.153 ±(99.9%) 5.649 ops/ms [Average]
  (min, avg, max) = (7.819, 8.153, 8.430), stdev = 0.310
  CI (99.9%): [2.504, 13.802] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.151 ops/ms
# Warmup Iteration   2: 6.659 ops/ms
# Warmup Iteration   3: 7.772 ops/ms
Iteration   1: 7.989 ops/ms
Iteration   2: 8.112 ops/ms
Iteration   3: 8.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.061 ±(99.9%) 1.173 ops/ms [Average]
  (min, avg, max) = (7.989, 8.061, 8.112), stdev = 0.064
  CI (99.9%): [6.889, 9.234] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.395 ops/ms
# Warmup Iteration   2: 5.896 ops/ms
# Warmup Iteration   3: 6.631 ops/ms
Iteration   1: 6.457 ops/ms
Iteration   2: 6.474 ops/ms
Iteration   3: 6.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.567 ±(99.9%) 3.222 ops/ms [Average]
  (min, avg, max) = (6.457, 6.567, 6.771), stdev = 0.177
  CI (99.9%): [3.345, 9.789] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 10.908 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.710 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.326 ±(99.9%) 0.009 ms/op
Iteration   1: 4.089 ±(99.9%) 0.004 ms/op
Iteration   2: 3.981 ±(99.9%) 0.007 ms/op
Iteration   3: 4.028 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.033 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (3.981, 4.033, 4.089), stdev = 0.054
  CI (99.9%): [3.044, 5.022] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.661 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.002 ms/op
Iteration   1: 3.826 ±(99.9%) 0.007 ms/op
Iteration   2: 3.761 ±(99.9%) 0.005 ms/op
Iteration   3: 3.737 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.775 ±(99.9%) 0.838 ms/op [Average]
  (min, avg, max) = (3.737, 3.775, 3.826), stdev = 0.046
  CI (99.9%): [2.937, 4.613] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.266 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.681 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.116 ±(99.9%) 0.004 ms/op
Iteration   1: 4.025 ±(99.9%) 0.004 ms/op
Iteration   2: 4.088 ±(99.9%) 0.004 ms/op
Iteration   3: 3.972 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.028 ±(99.9%) 1.061 ms/op [Average]
  (min, avg, max) = (3.972, 4.028, 4.088), stdev = 0.058
  CI (99.9%): [2.967, 5.089] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.361 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.372 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.741 ±(99.9%) 0.007 ms/op
Iteration   1: 4.716 ±(99.9%) 0.009 ms/op
Iteration   2: 4.592 ±(99.9%) 0.010 ms/op
Iteration   3: 4.688 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.665 ±(99.9%) 1.190 ms/op [Average]
  (min, avg, max) = (4.592, 4.665, 4.716), stdev = 0.065
  CI (99.9%): [3.475, 5.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.581 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 5.018 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.016 ms/op
Iteration   1: 4.138 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.440 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.850 ms/op
                 createUser·p0.95:   5.620 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  22.826 ms/op
                 createUser·p0.9999: 26.935 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   2: 3.914 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.632 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.415 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  14.254 ms/op
                 createUser·p0.9999: 26.837 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 4.054 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.511 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   7.700 ms/op
                 createUser·p0.999:  27.132 ms/op
                 createUser·p0.9999: 31.123 ms/op
                 createUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237935
  mean =      4.033 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 429 
    [ 2.500,  5.000) = 224431 
    [ 5.000,  7.500) = 10367 
    [ 7.500, 10.000) = 1760 
    [10.000, 12.500) = 492 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      7.845 ms/op
     p(99.9000) =     22.778 ms/op
     p(99.9900) =     29.461 ms/op
     p(99.9990) =     32.153 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.076 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.328 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.014 ms/op
Iteration   1: 4.039 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.567 ms/op
                 existUser·p0.50:   3.858 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   8.135 ms/op
                 existUser·p0.999:  22.442 ms/op
                 existUser·p0.9999: 25.431 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 3.909 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.892 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.350 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  13.457 ms/op
                 existUser·p0.9999: 26.307 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.935 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.980 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  11.021 ms/op
                 existUser·p0.9999: 33.751 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242271
  mean =      3.960 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 302 
    [ 2.500,  5.000) = 230781 
    [ 5.000,  7.500) = 9044 
    [ 7.500, 10.000) = 1346 
    [10.000, 12.500) = 476 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.567 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     33.252 ms/op
     p(99.9990) =     34.694 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.509 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.363 ±(99.9%) 0.018 ms/op
Iteration   1: 4.309 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   4.067 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   8.495 ms/op
                 getUser·p0.999:  25.526 ms/op
                 getUser·p0.9999: 36.382 ms/op
                 getUser·p1.00:   36.635 ms/op

Iteration   2: 4.073 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.966 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   7.905 ms/op
                 getUser·p0.999:  13.517 ms/op
                 getUser·p0.9999: 27.820 ms/op
                 getUser·p1.00:   28.344 ms/op

Iteration   3: 4.048 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.509 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  26.772 ms/op
                 getUser·p0.9999: 29.363 ms/op
                 getUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231768
  mean =      4.140 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 218587 
    [ 5.000,  7.500) = 10142 
    [ 7.500, 10.000) = 2142 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 152 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     25.526 ms/op
     p(99.9900) =     34.079 ms/op
     p(99.9990) =     36.569 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.945 ±(99.9%) 0.195 ms/op
# Warmup Iteration   2: 5.728 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.976 ±(99.9%) 0.017 ms/op
Iteration   1: 5.057 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  24.797 ms/op
                 listUser·p0.9999: 27.221 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   2: 4.700 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.773 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.178 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 27.984 ms/op
                 listUser·p1.00:   28.738 ms/op

Iteration   3: 4.892 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.927 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  17.887 ms/op
                 listUser·p0.9999: 22.983 ms/op
                 listUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196677
  mean =      4.879 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 146278 
    [ 5.000,  7.500) = 45927 
    [ 7.500, 10.000) = 3243 
    [10.000, 12.500) = 553 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      1.927 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      5.505 ms/op
     p(95.0000) =      6.054 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     22.184 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     28.389 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.818 ± 2.521  ops/ms
ClientPb.existUser                       thrpt       3   8.153 ± 5.649  ops/ms
ClientPb.getUser                         thrpt       3   8.061 ± 1.173  ops/ms
ClientPb.listUser                        thrpt       3   6.567 ± 3.222  ops/ms
ClientPb.createUser                       avgt       3   4.033 ± 0.989   ms/op
ClientPb.existUser                        avgt       3   3.775 ± 0.838   ms/op
ClientPb.getUser                          avgt       3   4.028 ± 1.061   ms/op
ClientPb.listUser                         avgt       3   4.665 ± 1.190   ms/op
ClientPb.createUser                     sample  237935   4.033 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.440           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.867           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.637           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.079           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.845           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.778           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.461           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.178           ms/op
ClientPb.existUser                      sample  242271   3.960 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.567           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.274           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.746           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.252           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.324           ms/op
ClientPb.getUser                        sample  231768   4.140 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.509           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.120           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.913           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.526           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.079           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.635           ms/op
ClientPb.listUser                       sample  196677   4.879 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.927           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.054           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.782           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.184           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.870           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.738           ms/op
