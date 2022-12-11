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
# Warmup Iteration   1: 1.690 ops/ms
# Warmup Iteration   2: 3.866 ops/ms
# Warmup Iteration   3: 7.335 ops/ms
Iteration   1: 7.348 ops/ms
Iteration   2: 8.558 ops/ms
Iteration   3: 8.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.023 ±(99.9%) 11.249 ops/ms [Average]
  (min, avg, max) = (7.348, 8.023, 8.558), stdev = 0.617
  CI (99.9%): [≈ 0, 19.271] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.325 ops/ms
# Warmup Iteration   2: 7.382 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 8.635 ops/ms
Iteration   2: 8.516 ops/ms
Iteration   3: 8.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.626 ±(99.9%) 1.937 ops/ms [Average]
  (min, avg, max) = (8.516, 8.626, 8.728), stdev = 0.106
  CI (99.9%): [6.689, 10.563] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.392 ops/ms
# Warmup Iteration   2: 6.905 ops/ms
# Warmup Iteration   3: 8.085 ops/ms
Iteration   1: 8.450 ops/ms
Iteration   2: 8.623 ops/ms
Iteration   3: 8.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.529 ±(99.9%) 1.592 ops/ms [Average]
  (min, avg, max) = (8.450, 8.529, 8.623), stdev = 0.087
  CI (99.9%): [6.937, 10.122] (assumes normal distribution)


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
# Warmup Iteration   1: 2.238 ops/ms
# Warmup Iteration   2: 6.161 ops/ms
# Warmup Iteration   3: 7.118 ops/ms
Iteration   1: 6.955 ops/ms
Iteration   2: 7.353 ops/ms
Iteration   3: 7.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.162 ±(99.9%) 3.633 ops/ms [Average]
  (min, avg, max) = (6.955, 7.162, 7.353), stdev = 0.199
  CI (99.9%): [3.529, 10.795] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.666 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.004 ms/op
Iteration   1: 3.904 ±(99.9%) 0.011 ms/op
Iteration   2: 3.773 ±(99.9%) 0.012 ms/op
Iteration   3: 3.823 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.833 ±(99.9%) 1.210 ms/op [Average]
  (min, avg, max) = (3.773, 3.833, 3.904), stdev = 0.066
  CI (99.9%): [2.623, 5.044] (assumes normal distribution)


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
# Warmup Iteration   1: 12.412 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.006 ms/op
Iteration   1: 3.770 ±(99.9%) 0.010 ms/op
Iteration   2: 3.482 ±(99.9%) 0.011 ms/op
Iteration   3: 3.745 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.666 ±(99.9%) 2.909 ms/op [Average]
  (min, avg, max) = (3.482, 3.666, 3.770), stdev = 0.159
  CI (99.9%): [0.756, 6.575] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.328 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.005 ms/op
Iteration   1: 3.764 ±(99.9%) 0.011 ms/op
Iteration   2: 3.695 ±(99.9%) 0.017 ms/op
Iteration   3: 3.776 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.745 ±(99.9%) 0.796 ms/op [Average]
  (min, avg, max) = (3.695, 3.745, 3.776), stdev = 0.044
  CI (99.9%): [2.950, 4.541] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 12.728 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.796 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.669 ±(99.9%) 0.010 ms/op
Iteration   1: 4.655 ±(99.9%) 0.007 ms/op
Iteration   2: 4.441 ±(99.9%) 0.017 ms/op
Iteration   3: 4.582 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.559 ±(99.9%) 1.978 ms/op [Average]
  (min, avg, max) = (4.441, 4.559, 4.655), stdev = 0.108
  CI (99.9%): [2.581, 6.538] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.189 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.871 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.018 ms/op
Iteration   1: 3.784 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.931 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  11.804 ms/op
                 createUser·p0.9999: 25.562 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   2: 3.834 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.301 ms/op
                 createUser·p0.999:  25.567 ms/op
                 createUser·p0.9999: 28.366 ms/op
                 createUser·p1.00:   30.507 ms/op

Iteration   3: 4.066 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.920 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  29.396 ms/op
                 createUser·p0.9999: 32.805 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 246576
  mean =      3.891 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1215 
    [ 2.500,  5.000) = 235713 
    [ 5.000,  7.500) = 8173 
    [ 7.500, 10.000) = 1000 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     23.738 ms/op
     p(99.9900) =     31.951 ms/op
     p(99.9990) =     33.940 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 10.330 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.009 ms/op
Iteration   1: 3.726 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.733 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  10.325 ms/op
                 existUser·p0.9999: 24.917 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   2: 3.785 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  22.659 ms/op
                 existUser·p0.9999: 26.057 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 3.678 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.815 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  12.714 ms/op
                 existUser·p0.9999: 28.506 ms/op
                 existUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 257328
  mean =      3.729 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2647 
    [ 2.500,  5.000) = 240964 
    [ 5.000,  7.500) = 12149 
    [ 7.500, 10.000) = 986 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.102 ms/op
     p(99.9900) =     27.149 ms/op
     p(99.9990) =     28.705 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 12.324 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.012 ms/op
Iteration   1: 3.918 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   8.696 ms/op
                 getUser·p0.999:  20.874 ms/op
                 getUser·p0.9999: 23.358 ms/op
                 getUser·p1.00:   23.921 ms/op

Iteration   2: 3.837 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  26.714 ms/op
                 getUser·p0.9999: 32.243 ms/op
                 getUser·p1.00:   33.325 ms/op

Iteration   3: 3.858 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  13.653 ms/op
                 getUser·p0.9999: 31.331 ms/op
                 getUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247909
  mean =      3.871 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 192 
    [ 2.500,  5.000) = 237054 
    [ 5.000,  7.500) = 8182 
    [ 7.500, 10.000) = 1559 
    [10.000, 12.500) = 514 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     31.366 ms/op
     p(99.9990) =     33.042 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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
# Warmup Iteration   1: 15.122 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.570 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.767 ±(99.9%) 0.017 ms/op
Iteration   1: 4.622 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  25.341 ms/op
                 listUser·p0.9999: 28.129 ms/op
                 listUser·p1.00:   28.770 ms/op

Iteration   2: 4.631 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 19.667 ms/op
                 listUser·p1.00:   20.382 ms/op

Iteration   3: 4.569 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.819 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   9.339 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208273
  mean =      4.607 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 183136 
    [ 5.000,  7.500) = 20586 
    [ 7.500, 10.000) = 3363 
    [10.000, 12.500) = 593 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.661 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     27.471 ms/op
     p(99.9990) =     28.473 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.023 ± 11.249  ops/ms
ClientPb.existUser                       thrpt       3   8.626 ±  1.937  ops/ms
ClientPb.getUser                         thrpt       3   8.529 ±  1.592  ops/ms
ClientPb.listUser                        thrpt       3   7.162 ±  3.633  ops/ms
ClientPb.createUser                       avgt       3   3.833 ±  1.210   ms/op
ClientPb.existUser                        avgt       3   3.666 ±  2.909   ms/op
ClientPb.getUser                          avgt       3   3.745 ±  0.796   ms/op
ClientPb.listUser                         avgt       3   4.559 ±  1.978   ms/op
ClientPb.createUser                     sample  246576   3.891 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.813            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.489            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.858            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.668            ms/op
ClientPb.createUser:createUser·p0.999   sample          23.738            ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.951            ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734            ms/op
ClientPb.existUser                      sample  257328   3.729 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.569            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.617            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.284            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.071            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.709            ms/op
ClientPb.existUser:existUser·p0.999     sample          13.102            ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.149            ms/op
ClientPb.existUser:existUser·p1.00      sample          28.705            ms/op
ClientPb.getUser                        sample  247909   3.871 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.176            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.695            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.383            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.833            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.504            ms/op
ClientPb.getUser:getUser·p0.999         sample          20.414            ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.366            ms/op
ClientPb.getUser:getUser·p1.00          sample          33.325            ms/op
ClientPb.listUser                       sample  208273   4.607 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.661            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.432            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.104            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.579            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.684            ms/op
ClientPb.listUser:listUser·p0.999       sample          18.547            ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.471            ms/op
ClientPb.listUser:listUser·p1.00        sample          28.770            ms/op
