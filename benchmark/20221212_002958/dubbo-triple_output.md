# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.925 ops/ms
# Warmup Iteration   2: 4.443 ops/ms
# Warmup Iteration   3: 7.850 ops/ms
Iteration   1: 8.040 ops/ms
Iteration   2: 8.156 ops/ms
Iteration   3: 8.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.198 ±(99.9%) 3.324 ops/ms [Average]
  (min, avg, max) = (8.040, 8.198, 8.397), stdev = 0.182
  CI (99.9%): [4.874, 11.522] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.625 ops/ms
# Warmup Iteration   2: 7.544 ops/ms
# Warmup Iteration   3: 8.554 ops/ms
Iteration   1: 8.848 ops/ms
Iteration   2: 8.922 ops/ms
Iteration   3: 8.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.921 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (8.848, 8.921, 8.993), stdev = 0.072
  CI (99.9%): [7.600, 10.241] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.399 ops/ms
# Warmup Iteration   2: 7.273 ops/ms
# Warmup Iteration   3: 8.449 ops/ms
Iteration   1: 8.181 ops/ms
Iteration   2: 8.481 ops/ms
Iteration   3: 8.819 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.494 ±(99.9%) 5.824 ops/ms [Average]
  (min, avg, max) = (8.181, 8.494, 8.819), stdev = 0.319
  CI (99.9%): [2.669, 14.318] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.674 ops/ms
# Warmup Iteration   2: 5.850 ops/ms
# Warmup Iteration   3: 7.295 ops/ms
Iteration   1: 7.117 ops/ms
Iteration   2: 7.520 ops/ms
Iteration   3: 7.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.353 ±(99.9%) 3.826 ops/ms [Average]
  (min, avg, max) = (7.117, 7.353, 7.520), stdev = 0.210
  CI (99.9%): [3.527, 11.179] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.570 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.009 ms/op
Iteration   1: 3.662 ±(99.9%) 0.006 ms/op
Iteration   2: 3.646 ±(99.9%) 0.006 ms/op
Iteration   3: 3.799 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.702 ±(99.9%) 1.542 ms/op [Average]
  (min, avg, max) = (3.646, 3.702, 3.799), stdev = 0.085
  CI (99.9%): [2.160, 5.244] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.766 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.004 ms/op
Iteration   1: 3.474 ±(99.9%) 0.005 ms/op
Iteration   2: 3.576 ±(99.9%) 0.007 ms/op
Iteration   3: 3.478 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.509 ±(99.9%) 1.054 ms/op [Average]
  (min, avg, max) = (3.474, 3.509, 3.576), stdev = 0.058
  CI (99.9%): [2.455, 4.563] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.872 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.208 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.005 ms/op
Iteration   1: 3.793 ±(99.9%) 0.009 ms/op
Iteration   2: 3.732 ±(99.9%) 0.008 ms/op
Iteration   3: 3.994 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.840 ±(99.9%) 2.498 ms/op [Average]
  (min, avg, max) = (3.732, 3.840, 3.994), stdev = 0.137
  CI (99.9%): [1.341, 6.338] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.891 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.436 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.661 ±(99.9%) 0.006 ms/op
Iteration   1: 4.492 ±(99.9%) 0.010 ms/op
Iteration   2: 4.259 ±(99.9%) 0.009 ms/op
Iteration   3: 4.402 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.384 ±(99.9%) 2.150 ms/op [Average]
  (min, avg, max) = (4.259, 4.384, 4.492), stdev = 0.118
  CI (99.9%): [2.235, 6.534] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.397 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.696 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.017 ms/op
Iteration   1: 3.811 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  23.529 ms/op
                 createUser·p0.9999: 27.250 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   2: 3.756 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.788 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  11.026 ms/op
                 createUser·p0.9999: 27.279 ms/op
                 createUser·p1.00:   27.951 ms/op

Iteration   3: 3.637 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.571 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.689 ms/op
                 createUser·p0.999:  25.397 ms/op
                 createUser·p0.9999: 29.839 ms/op
                 createUser·p1.00:   32.604 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 257038
  mean =      3.733 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2275 
    [ 2.500,  5.000) = 245441 
    [ 5.000,  7.500) = 7716 
    [ 7.500, 10.000) = 1102 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 128 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     17.232 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.361 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.010 ms/op
Iteration   1: 3.903 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.673 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   8.176 ms/op
                 existUser·p0.999:  23.200 ms/op
                 existUser·p0.9999: 30.966 ms/op
                 existUser·p1.00:   31.719 ms/op

Iteration   2: 3.578 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   6.617 ms/op
                 existUser·p0.999:  10.699 ms/op
                 existUser·p0.9999: 28.969 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   3: 3.653 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.599 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  27.694 ms/op
                 existUser·p0.9999: 36.651 ms/op
                 existUser·p1.00:   40.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 258763
  mean =      3.706 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 245519 
    [ 5.000, 10.000) = 12705 
    [10.000, 15.000) = 251 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 67 
    [25.000, 30.000) = 116 
    [30.000, 35.000) = 45 
    [35.000, 40.000) = 27 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     35.930 ms/op
     p(99.9990) =     40.116 ms/op
     p(99.9999) =     40.567 ms/op
    p(100.0000) =     40.567 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.966 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.015 ms/op
Iteration   1: 3.728 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  23.298 ms/op
                 getUser·p0.9999: 27.460 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   2: 3.954 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   6.316 ms/op
                 getUser·p0.99:   8.233 ms/op
                 getUser·p0.999:  18.252 ms/op
                 getUser·p0.9999: 27.437 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 3.792 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  27.712 ms/op
                 getUser·p0.9999: 31.017 ms/op
                 getUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 250939
  mean =      3.823 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2281 
    [ 2.500,  5.000) = 234625 
    [ 5.000,  7.500) = 11187 
    [ 7.500, 10.000) = 1967 
    [10.000, 12.500) = 439 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     23.069 ms/op
     p(99.9900) =     30.242 ms/op
     p(99.9990) =     31.227 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.085 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.166 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.440 ±(99.9%) 0.016 ms/op
Iteration   1: 4.449 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  25.495 ms/op
                 listUser·p0.9999: 27.612 ms/op
                 listUser·p1.00:   29.655 ms/op

Iteration   2: 4.401 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 21.201 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 4.461 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   8.243 ms/op
                 listUser·p0.999:  16.253 ms/op
                 listUser·p0.9999: 19.781 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 216408
  mean =      4.437 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 192676 
    [ 5.000,  7.500) = 19920 
    [ 7.500, 10.000) = 2696 
    [10.000, 12.500) = 463 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     18.140 ms/op
     p(99.9900) =     26.324 ms/op
     p(99.9990) =     29.000 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.198 ± 3.324  ops/ms
ClientPb.existUser                       thrpt       3   8.921 ± 1.321  ops/ms
ClientPb.getUser                         thrpt       3   8.494 ± 5.824  ops/ms
ClientPb.listUser                        thrpt       3   7.353 ± 3.826  ops/ms
ClientPb.createUser                       avgt       3   3.702 ± 1.542   ms/op
ClientPb.existUser                        avgt       3   3.509 ± 1.054   ms/op
ClientPb.getUser                          avgt       3   3.840 ± 2.498   ms/op
ClientPb.listUser                         avgt       3   4.384 ± 2.150   ms/op
ClientPb.createUser                     sample  257038   3.733 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.157           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.637           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.661           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.232           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.606           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.604           ms/op
ClientPb.existUser                      sample  258763   3.706 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.104           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.160           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.857           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.930           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.567           ms/op
ClientPb.getUser                        sample  250939   3.823 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.188           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.069           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.242           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.588           ms/op
ClientPb.listUser                       sample  216408   4.437 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.550           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.046           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.140           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.324           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.655           ms/op
